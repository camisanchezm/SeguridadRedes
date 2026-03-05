# Reto
MatchTheRegex
## Descripción
How about trying to match a regular expressionThe website is running [here](http://saturn.picoctf.net:54615/).
## Solución
picoCTF{succ3ssfully_matchtheregex_9080e406}
## Notas
Se inspeccionó el código fuente, tomando en cuenta esta parte de código la función de request e intentamos colocar picoCTF como entrada
```
function send_request() { let val = document.getElementById("name").value; // ^p.....F!? fetch(`/flag?input=${val}`) .then(res => res.text()) .then(res => { const res_json = JSON.parse(res); alert(res_json.flag) return false; }) return false; }
```
## Referencias
https://medium.com/@Gumn4m1/matchtheregex-9547b28e2ea0