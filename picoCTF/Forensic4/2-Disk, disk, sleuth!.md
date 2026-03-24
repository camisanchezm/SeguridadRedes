# Reto
Disk, disk, sleuth!

## Descripción
Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image.[dds1-alpine.flag.img.gz](https://challenge-files.picoctf.net/c_wily_courier/a7895bbce833fd95502d3a661fa54735e90d9bec9346d711ff05cbd40b5f3c8e/dds1-alpine.flag.img.gz)
## Solución
```
picoCTF{f0r3ns1c4t0r_n30phyt3_5e56e786}
```
## Notas
```
┌──(kali㉿kali)-[~/picoCTF/forensic/diskdisksle]
└─$ gzip -d dds1-alpine.flag.img.gz 
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/picoCTF/forensic/diskdisksle]
└─$ ls                              
dds1-alpine.flag.img
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/picoCTF/forensic/diskdisksle]
└─$ strings dds1-alpine.flag.img | grep pico          
ffffffff81399ccf t pirq_pico_get
ffffffff81399cee t pirq_pico_set
ffffffff820adb46 t pico_router_probe
  SAY picoCTF{f0r3ns1c4t0r_n30phyt3_5e56e786}
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/picoCTF/forensic/diskdisksle]
└─$
```
## Referencias
