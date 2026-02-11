# Reto
## Descripción
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...[warm](https://challenge-files.picoctf.net/c_wily_courier/c293351e09ee53217c6a868e7f98a0a2ba0cf9cdc4e4ed0e18f685d47111c216/warm)
## Solución
camilaa3-picoctf@webshell:~$ file warm
```
warm: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, BuildID[sha1]=9e46ec8729d2f2aa8ffc4b1cdc058081bddcfe67, for GNU/Linux 3.2.0, with debug_info, not stripped
camilaa3-picoctf@webshell:~$ chmod +x warm
camilaa3-picoctf@webshell:~$ ./warm
Hello user! Pass me a -h to learn what I can do!
camilaa3-picoctf@webshell:~$ ./warm -h
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_ac5832c}
```
## Notas
**chmod +x** agrega permisos de ejecución
**./warm** ejecuta el archivo
**-h** pide ayuda
## Referencias