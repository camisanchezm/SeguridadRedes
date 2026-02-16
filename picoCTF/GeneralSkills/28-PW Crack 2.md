# Reto
PW Crack 2
## Descripción
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/14/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/14/level2.flag.txt.enc) in the same directory too.
## Solución
```
camilaa3-picoctf@webshell:~$ wget -q https://artifacts.picoctf.net/c/14/level2.py
camilaa3-picoctf@webshell:~$ wget -q https://artifacts.picoctf.net/c/14/level2.flag.txt.enc
camilaa3-picoctf@webshell:~$ nano level2.py
camilaa3-picoctf@webshell:~$ python level2.py
4ec9
Please enter correct password for flag: 4ec9
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_9701e681}
```
## Notas
Igual que en el reto anterior el password venía implícito en un if, pero en caracter, solo se usó un print para que los convirtiera y formara una cadena
```
def level_2_pw_check():
    print(chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39))
    user_pw = input("Please enter correct password for flag: ")
  
    if( user_pw == chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39) ):
```

## Referencias