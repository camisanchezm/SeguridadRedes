# Reto
## Descripción
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/12/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/12/level1.flag.txt.enc) in the same directory too.
## Solución
```
camilaa3-picoctf@webshell:~$ nano level1.py
camilaa3-picoctf@webshell:~$ python level1.py
Please enter correct password for flag: 8713
Welcome back... your flag, user:
picoCTF{545h_r1ng1ng_1b2fd683}
```
## Notas
Entramos al código fuente del archivo y dentro de un if se encontraba el password
```
def level_1_pw_check():
    user_pw = input("Please enter correct password for flag: ")
    **if( user_pw == "8713"):**
        print("Welcome back... your flag, user:")
        decryption = str_xor(flag_enc.decode(), user_pw)
        print(decryption)
        return
    print("That password is incorrect")
```
## Referencias