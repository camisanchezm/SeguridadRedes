# Reto
Based
## Descripción
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337?Connect with nc fickle-tempest.picoctf.net 49594.
## Solución
Primero nos conectamos al puerto indicado, después con ayuda de cyberchef convertimos los valores solicitados
```
camilaa3-picoctf@webshell:~$ nc fickle-tempest.picoctf.net 49594
Let us see how data is stored
lamp
Please give the 01101100 01100001 01101101 01110000 as a word.
...
you have 45 seconds.....

Input:
lamp
Please give me the  o146 o141 o154 o143 o157 o156 as a word.
Input:
falcon
Please give me the 6c69676874 as a word.
Input:
light
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_563BAF26}
```
## Notas
## Referencias
Octal
https://gchq.github.io/CyberChef/#recipe=From_Hex('None')&input=NmM2OTY3Njg3NA
Hexadecimal
https://gchq.github.io/CyberChef/#recipe=Find_/_Replace(%7B'option':'Regex','string':'o'%7D,'',true,false,true,false)From_Octal('Space')&input=bzE0NiBvMTQxIG8xNTQgbzE0MyBvMTU3IG8xNTY
Binario
https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8)&input=MDExMDExMDAgMDExMDAwMDEgMDExMDExMDEgMDExMTAwMDA
