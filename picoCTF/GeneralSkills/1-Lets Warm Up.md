## Lets Warm Up
## Descripción
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?
## Solución
## Solución 1
- Usando cyberchef
- https://gchq.github.io/CyberChef/#recipe=From_Hex('0x')&input=MHg3MA
## Solución 2
- Usando Python
```
>>> int(0x70)
112
>>> chr(112)
'p'
>>> ord('p')
112
```
picoCTF{p}
## Notas
Usamos la pagina de cyberchef para descifrar codificaciones
## Referencias
https://gchq.github.io/CyberChef/