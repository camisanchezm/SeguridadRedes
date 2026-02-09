# Reto
## Bases
## Descripción
What does this bDNhcm5fdGgzX3IwcDM1 mean? I think it has something to do with bases.
## Solución
Primero debemos identificar con que tipo de formato "base" estaremos trabajando, en este caso es Base64, luego en la terminal de picoCTF se colocó lo siguiente:
```
echo "bDNhcm5fdGgzX3IwcDM1" | base64 --decode
```
## Notas
Se consultó la página "Medium" para poder solucionar el problema
## Referencias
https://medium.com/@Pr0tego/picoctf-bases-walkthrough-5f701424f5cb