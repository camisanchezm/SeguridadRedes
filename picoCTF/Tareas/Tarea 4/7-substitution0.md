## Reto
substitution0
## Descripción
A message has come in but it seems to be all scrambled. Luckily it seems to have the key at the beginning. Can you crack this substitution cipher? Download the message [here](https://artifacts.picoctf.net/c/153/message.txt).
## Solución
picoCTF{5UB5717U710N_3V0LU710N_357BF9FF}
## Notas
Se realizó un cat al archivo, obteniendo lo siguiente:
ZGSOCXPQUYHMILERVTBWNAFJDK 

  

Qctcnrel Mcptzlo ztebc, fuwq z ptzac zlo bwzwcmd zut, zlo gtenpqw ic wqc gccwmc

xtei z pmzbb szbc ul fqusq uw fzb clsmebco. Uw fzb z gcznwuxnm bsztzgzcnb, zlo, zw

wqzw wuic, nlhlefl we lzwntzmubwb—ex sentbc z ptczw rtukc ul z bsuclwuxus reulw

ex aucf. Wqctc fctc wfe tenlo gmzsh brewb lczt elc cjwtciuwd ex wqc gzsh, zlo z

melp elc lczt wqc ewqct. Wqc bszmcb fctc cjsccoulpmd qzto zlo pmebbd, fuwq zmm wqc

zrrcztzlsc ex gntlubqco pemo. Wqc fcupqw ex wqc ulbcsw fzb actd tcizthzgmc, zlo,

wzhulp zmm wqulpb ulwe selbuoctzwuel, U senmo qztomd gmzic Ynruwct xet qub eruluel

tcbrcswulp uw.

  

Wqc xmzp ub: ruseSWX{5NG5717N710L_3A0MN710L_357GX9XX}**%**
Y se decodificó en cyberchef
Plaintext: ZGSOCXPQUYHMILERVTBWNAFJDKzgsocxpquyhmilervtbwnafjdk
Ciphertext: ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxy
## Referencias
https://toolbox.itsec.tamu.edu/#recipe=Substitute('ZGSOCXPQUYHMILERVTBWNAFJDKzgsocxpquyhmilervtbwnafjdk','ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxy',false)&input=WkdTT0NYUFFVWUhNSUxFUlZUQldOQUZKREsgCgpRY3RjbnJlbCBNY3B0emxvIHp0ZWJjLCBmdXdxIHogcHR6YWMgemxvIGJ3endjbWQgenV0LCB6bG8gZ3RlbnBxdyBpYyB3cWMgZ2Njd21jCnh0ZWkgeiBwbXpiYiBzemJjIHVsIGZxdXNxIHV3IGZ6YiBjbHNtZWJjby4gVXcgZnpiIHogZ2N6bnd1eG5tIGJzenR6Z3pjbmIsIHpsbywgencKd3F6dyB3dWljLCBubGhsZWZsIHdlIGx6d250em11Yndi4oCUZXggc2VudGJjIHogcHRjencgcnR1a2MgdWwgeiBic3VjbHd1eHVzIHJldWx3CmV4IGF1Y2YuIFdxY3RjIGZjdGMgd2ZlIHRlbmxvIGdtenNoIGJyZXdiIGxjenQgZWxjIGNqd3RjaXV3ZCBleCB3cWMgZ3pzaCwgemxvIHoKbWVscCBlbGMgbGN6dCB3cWMgZXdxY3QuIFdxYyBic3ptY2IgZmN0YyBjanNjY291bHBtZCBxenRvIHpsbyBwbWViYmQsIGZ1d3Egem1tIHdxYwp6cnJjenR6bHNjIGV4IGdudGx1YnFjbyBwZW1vLiBXcWMgZmN1cHF3IGV4IHdxYyB1bGJjc3cgZnpiIGFjdGQgdGNpenRoemdtYywgemxvLAp3emh1bHAgem1tIHdxdWxwYiB1bHdlIHNlbGJ1b2N0end1ZWwsIFUgc2VubW8gcXp0b21kIGdtemljIFlucnV3Y3QgeGV0IHF1YiBlcnVsdWVsCnRjYnJjc3d1bHAgdXcuCgpXcWMgeG16cCB1YjogcnVzZVNXWHs1Tkc1NzE3TjcxMExfM0EwTU43MTBMXzM1N0dYOVhYfSUgICA