## Reto
## Descripción
## Solución
picoCTF{p@g3_turn3r_0c0d211f}
## Notas
La pagina nos da un codigo en javascript

        javascript:(function() {
            var encryptedFlag = "àÒÆÞ¦È¬ëÙ£Ö�ÓÚåÛÑ¢ÕÓ�ÒËÉ§�©�í";
            var key = "picoctf";
            var decryptedFlag = "";
            for (var i = 0; i < encryptedFlag.length; i++) {
                decryptedFlag += String.fromCharCode((encryptedFlag.charCodeAt(i) - key.charCodeAt(i % key.length) + 256) % 256);
            }
            alert(decryptedFlag);
        })();
    
Lo corremos y nos da la flag
picoCTF{p@g3_turn3r_0c0d211f}
## Referencias
