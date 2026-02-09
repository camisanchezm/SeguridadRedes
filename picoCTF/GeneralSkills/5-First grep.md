# Reto
First grep
## Descripción
Can you find the flag in the file? This would be really tedious to look through manually, something tells me there is a better way. The flag is in this [file](https://challenge-files.picoctf.net/c_fickle_tempest/b8915fc817a2cd58e83d7e779515ed3f898738d12cf1974086f8ba3f515ae3cf/file).
## Solución
En la terminal ingresas a la carpeta donde está descargado el archivo file, luego se ingresa el siguiente comando:
```
a@Camilas-MacBook-Pro downloads % grep --color=auto -o 'picoCTF{[^}]*}' file
**picoCTF{grep_is_good_to_find_things_beD770f5}**
```
## Notas
## Referencias
https://medium.com/@walterchristian28/picoctf-2019-first-grep-601cced5392a
