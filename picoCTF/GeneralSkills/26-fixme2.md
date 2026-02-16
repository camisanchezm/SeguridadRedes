# Reto
## Descripción
Fix the syntax error in the Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/6/fixme2.py)
## Solución
```
camilaa3-picoctf@webshell:~$ python fixme2.py
  File "/home/camilaa3-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
camilaa3-picoctf@webshell:~$ nano fixme2.py
camilaa3-picoctf@webshell:~$ python fixme2.py
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_f6a5aefc}
```
## Notas
Se solucionó el código en python, faltaba un = en un if
## Referencias