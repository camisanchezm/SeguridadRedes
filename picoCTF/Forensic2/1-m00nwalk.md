# Reto
## Descripción
Decode this [message](https://challenge-files.picoctf.net/c_fickle_tempest/f75cb0bb148301a92ee34a572e39d931d62c9c225f69e4b801ffa0fb6d2fe17b/message.wav) from the moon.
## Solución
picoCTF{beep_boop_im_in_space}
## Notas
Se utilizó una herramienta para decodificar el audio la cual se extrajo de github con el siguiente comando 
```
$ git clone https://github.com/colaclanth/sstv.git

$ python setup.py install
```
Luego se usó el siguiente comando 
```
sstv -d message.wav.1 -o result.png
```
## Referencias
