# Reto
Glory of the garden
## Descripción
This file contains more than it seems.Get the flag from [garden.jpg](https://challenge-files.picoctf.net/c_fickle_tempest/150b6eaad43200d3dc91f98c390e4c6168620b57d0b95a7e9d04c92910bbbe16/garden.jpg).
## Solución
picoCTF{more_than_m33ts_the_3y3a63b5b27}
## Notas
Usando la webshell de pico se descargó la imagen con un wget, luego se colocaron los siguientes comandos
```
camilaa3-picoctf@webshell:~$ strings garden.jpg > strings.txt
camilaa3-picoctf@webshell:~$ wc -l strings.txt
28584 strings.txt
camilaa3-picoctf@webshell:~$ cat strings | grep pico
cat: strings: No such file or directory
camilaa3-picoctf@webshell:~$ cat strings.txt | grep pico
Here is a flag: picoCTF{more_than_m33ts_the_3y3a63b5b27}
```
## Referencias
https://play.picoctf.org/practice