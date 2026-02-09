# Reto
Nice netcat
## Descripción
There is a nice program that you can talk to by using this command in a shell:$ nc wily-courier.picoctf.net 65401, but it doesn't speak English...
## Solución
Ingresamos el siguiente comando en la terminal, los valores obtenidos deben de ser descifrados y para eso utilizamos python
```
camilaa3-picoctf@webshell:~$ nc wily-courier.picoctf.net 65401
```
```
camilaa3-picoctf@webshell:~$ python3 -c 'print("".join([chr(n) for n in [
> 112, 105, 99, 111, 67, 84, 70, 123,
> 103, 48, 48, 100, 95, 107, 49, 116,
> 116, 121, 33, 95, 110, 49, 99, 51,
>  95, 107, 49, 116, 116, 121, 33, 95,
> 100, 57, 52, 55, 54, 125, 10
> ]]))'
picoCTF{g00d_k1tty!_n1c3_k1tty!_d9476}
```
## Notas
## Referencias
