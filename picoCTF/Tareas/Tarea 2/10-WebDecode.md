# Reto
WebDecode
## Descripción
Do you know how to use the web inspector?Start searching [here](http://titan.picoctf.net:57167/) to find the flag
## Solución
picoCTF{web_succ3ssfully_d3c0ded_1f832615}
## Notas
Se inspeccionó la pagina en donde se descubrió un pedazo de código y ese pedazo se decodificó
```
a@Camilas-MacBook-Pro ~ % echo cGljb0NURnt3ZWJfc3VjYzNzc2Z1bGx5X2QzYzBkZWRfMWY4MzI2MTV9 | base64 -d

picoCTF{web_succ3ssfully_d3c0ded_1f832615}**%**
```
## Referencias
https://medium.com/@Kamal_S/picoctf-web-exploitation-webdecode-2fb5f668eae6