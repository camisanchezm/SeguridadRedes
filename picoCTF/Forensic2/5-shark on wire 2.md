# Reto
## Descripción
We found this [packet capture](https://challenge-files.picoctf.net/c_fickle_tempest/4d884ac4c144f7871b97b96ae69a31a8483651db7929cd4ecb05d7447832f87c/capture.pcap). Recover the flag.
## Solución
picoCTF{p1LLf3r3d_data_v1a_st3g0}
## Notas
Se crea un exp.py con el siguiente contenido
```
from scapy.all import * packets = rdpcap('capture.pcap') flag='' for p in packets: if UDP in p and p[UDP].dport == 22: if p[UDP].sport > 5000: flag+=chr(p[UDP].sport - 5000) print(flag)
```
## Referencias