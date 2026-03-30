## Reto
## Descripción
## Solución
picoCTF{Hiddinng_An_imag3_within_@n_ima9e_d55982e8}
## Notas
```
a@Camilas-MacBook-Pro hideme % binwalk -e flag.png
**/Users/a/Downloads/hideme/extractions/flag.png**
**-------------------------------------------------------------------------------------------------------------------------------**
**DECIMAL                            HEXADECIMAL                        DESCRIPTION**
**-------------------------------------------------------------------------------------------------------------------------------**

0                                  0x0                                PNG image, total size: 39739 bytes

39739                              0x9B3B                             ZIP archive, file count: 2, total size: 3198 bytes

**-------------------------------------------------------------------------------------------------------------------------------**

**[#] Extraction of png data at offset 0x0 declined**

**[+] Extraction of zip data at offset 0x9B3B completed successfully**

**-------------------------------------------------------------------------------------------------------------------------------**
Analyzed 1 file for 85 file signatures (187 magic patterns) in 53.0 milliseconds

a@Camilas-MacBook-Pro hideme % ls

extractions flag.png

a@Camilas-MacBook-Pro hideme % cd extractions

a@Camilas-MacBook-Pro extractions % ls

flag.png flag.png.extracted

a@Camilas-MacBook-Pro extractions % cd flag.png.extracted

a@Camilas-MacBook-Pro flag.png.extracted % ls

9B3B

a@Camilas-MacBook-Pro flag.png.extracted % cd 9B3B

a@Camilas-MacBook-Pro 9B3B % ls

secret

a@Camilas-MacBook-Pro 9B3B % cd secret

a@Camilas-MacBook-Pro secret % ls

flag.png

a@Camilas-MacBook-Pro secret % open flag.png
```
## Referencias
