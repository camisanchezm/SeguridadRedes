# Reto
## 2Warm
## Descripción
Can you convert the number 42 (base 10) to binary (base 2)?
## Solución
42 ÷ 2 = 21 residuo 0
21 ÷ 2 = 10 residuo 1
10 ÷ 2 = 5 residuo 0
5÷ 2 = 2 residuo 1
2÷ 2 = 1 residuo 0
1 ÷ 2 = 0 residuo 1
Leemos de abajo para arriba y obtenemos la composición del número en binario 101010
## Solución 2
Utilizamos python
```
camilaa3-picoctf@webshell:~$ python
Python 3.10.12 (main, Feb  4 2025, 14:57:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> bin(42)
'0b101010
```
Se investigó el método de conversión y se realizó manualmente
## Referencias
https://www.binarymath.net/decimal-to-binary.php
