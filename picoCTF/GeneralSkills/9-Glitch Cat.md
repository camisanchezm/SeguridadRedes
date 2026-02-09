# Reto
Glitch Cat
## Descripción
Our flag printing service has started glitching!`$ nc saturn.picoctf.net 60680`
## Solución

```
camilaa3-picoctf@webshell:~$ nc saturn.picoctf.net 60680 | grep picoCTF
'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'
```
La bandera aún no está completa, debemos de cambiar su formato hexa a decimal, para lo cual utilizamos los siguiente
```
camilaa3-picoctf@webshell:~$ python3 -c "print('picoCTF{gl17ch_m3_n07_' + ''.join(chr(x) for x in [0x61,0x34,0x33,0x39,0x32,0x64,0x32,0x65]) + '}')"
```
picoCTF{gl17ch_m3_n07_a4392d2e}
## Notas
## Referencias
