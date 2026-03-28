# Reto
HashingJobApp
## Descripción
If you want to hash with the best, beat this test!`nc saturn.picoctf.net 52283`
## Solución
picoCTF{4ppl1c4710n_r3c31v3d_3eb82b73}
## Notas
```

a@Camilas-MacBook-Pro ~ % nc saturn.picoctf.net 52283
Please md5 hash the text between quotes, excluding the quotes: 'a used car lot'
Answer: 
1a78bc064f8df8b4192ce5f8972c9b80
1a78bc064f8df8b4192ce5f8972c9b80
Correct.
Please md5 hash the text between quotes, excluding the quotes: 'Helen Keller'
Answer: 
c0aac1554fe46e67f218df124c318054
c0aac1554fe46e67f218df124c318054
Correct.
Please md5 hash the text between quotes, excluding the quotes: 'leeches'
Answer: 
1719980de08011881ae8f13c90baaa92
1719980de08011881ae8f13c90baaa92
Correct.
picoCTF{4ppl1c4710n_r3c31v3d_3eb82b73}
```

Se decodificó de la siguiente manera
```
a@Camilas-MacBook-Pro ~ % echo -n "stun guns" | md5
d1bc34c1bbadaea803f9ab0284e25adf
a@Camilas-MacBook-Pro ~ % echo -n "a used car lot" | md5
1a78bc064f8df8b4192ce5f8972c9b80
a@Camilas-MacBook-Pro ~ % echo -n "Helen Keller" | md5  
c0aac1554fe46e67f218df124c318054
a@Camilas-MacBook-Pro ~ % echo -n "leeches" | md5
```

## Referencias