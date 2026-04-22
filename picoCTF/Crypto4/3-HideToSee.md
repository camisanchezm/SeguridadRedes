## Reto
How about some hide and seek heh?Look at this image [here](https://artifacts.picoctf.net/c/240/atbash.jpg).
## Descripción
How about some hide and seek heh?Look at this image [here](https://artifacts.picoctf.net/c/240/atbash.jpg).
## Solución
picoCTF{atbash_crack_ca00558b}
## Notas
┌──(kali㉿kali)-[~/picoCTF/Crypto/hidetosee]
└─$ steghide extract -sf atbash.jpg
Anotar salvoconducto: 
anot� los datos extra�dos e/"encrypted.txt".
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/picoCTF/Crypto/hidetosee]
└─$ ls
atbash.jpg  encrypted.txt
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/picoCTF/Crypto/hidetosee]
└─$ cat encrypted.txt 
krxlXGU{zgyzhs_xizxp_1u84w779}

Usamos cyberchef con y le mandamos cifrado atbash
picoCTF{atbash_crack_ca00558b}
## Referencias
