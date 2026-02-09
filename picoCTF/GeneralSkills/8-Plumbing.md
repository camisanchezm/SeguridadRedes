# Reto
Plumbing
## Descripción
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to fickle-tempest.picoctf.net 56081.Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to fickle-tempest.picoctf.net 56081.
## Solución
```
camilaa3-picoctf@webshell:~$ nc fickle-tempest.picoctf.net 56081 | grep -o 'picoCTF{[^}]*}'
picoCTF{digital_plumb3r_A01Bc3eC}
```
## Referencias