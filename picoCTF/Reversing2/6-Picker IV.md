## Reto
Picker IV
## Descripción
Can you figure out how this program works to get the flag?

Additional details will be available after launching your challenge instance.
## Solución
picoCTF{n3v3r_jump_t0_u53r_5uppl13d_4ddr35535_01672a61}
## Notas

```
#include <stdio.h>

#include <stdlib.h>

#include <signal.h>

#include <unistd.h>

  
  

void print_segf_message(){

printf("Segfault triggered! Exiting.\n");

sleep(15);

exit(SIGSEGV);

}

  

int win() {

FILE *fptr;

char c;

  

printf("You won!\n");

// Open file

fptr = fopen("flag.txt", "r");

if (fptr == NULL)

{

printf("Cannot open file.\n");

exit(0);

}

  

// Read contents from file

c = fgetc(fptr);

while (c != EOF)

{

printf ("%c", c);

c = fgetc(fptr);

}

  

printf("\n");

fclose(fptr);

}

  

int main() {

signal(SIGSEGV, print_segf_message);

setvbuf(stdout, NULL, _IONBF, 0); // _IONBF = Unbuffered

  

unsigned int val;

printf("Enter the address in hex to jump to, excluding '0x': ");

scanf("%x", &val);

printf("You input 0x%x\n", val);

  

void (*foo)(void) = (void (*)())val;

foo();

}
```

```
a@Camilas-MacBook-Pro ~ % nc saturn.picoctf.net 65201

Enter the address in hex to jump to, excluding '0x': 40129e

You input 0x40129e

You won!

picoCTF{n3v3r_jump_t0_u53r_5uppl13d_4ddr35535_01672a61}
```
## Referencias
