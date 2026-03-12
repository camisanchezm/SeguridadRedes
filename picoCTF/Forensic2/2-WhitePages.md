# Reto
WhitePages
## Descripción
## Solución
picoCTF{not_all_spaces_are_created_equal_f62118c302bc9c9791e81915c805af3d}
## Notas
Se utilizaron los siguientes comandos 
```
xxd -g 1 -l 100 whitepages.txt
sed 's/\xe2\x80\x83/0/g' whitepages.txt | sed 's/\x20/1/g'
```
Y luego el resultado en binario se convirtió a caracteres con ayuda de cyberchef
## Referencias
https://gchq.github.io/CyberChef/