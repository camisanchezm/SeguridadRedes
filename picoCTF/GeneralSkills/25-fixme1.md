# Reto
## Descripción
Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/27/fixme1.py)
## Solución
```
camilaa3-picoctf@webshell:~$ python fixme1.py
  File "/home/camilaa3-picoctf/fixme1.py", line 20
    print('That is correct! Here\'s your flag: ' + flag)
IndentationError: unexpected indent
camilaa3-picoctf@webshell:~$ nano fixme1.py
camilaa3-picoctf@webshell:~$ python fixme1.py
That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_182342f7}
```
## Notas
Con nano solucionamos un error de indentacion en el archivo .py
## Referencias