# Deno vs Node: crypto edition

## Deno

```js

Daddie@Greeffer MINGW64 /d/Projects/binance-signature
$ Deno run --allow-all main.js
hashing the string: 
timestamp=1578963600000
and return:
d84e6641b1e328e7b418fff030caed655c266299c9355e36ce801ed14631eed4



hashing the string:
symbol=LTCBTC&side=BUY&type=LIMIT&timeInForce=GTC&quantity=1&price=0.1&recvWindow=5000&timestamp=1499827319559
and return:
c8db56825ae71d6d79447849e617115f4a920fa2acdcab2b053c4b2838bd6b71

Daddie@Greeffer MINGW64 /d/Projects/binance-signature
$
```

---
---

## Node

```js

Daddie@Greeffer MINGW64 /d/Projects/binance-signature
$ node main
hashing the string:
timestamp=1578963600000
and return:
d84e6641b1e328e7b418fff030caed655c266299c9355e36ce801ed14631eed4


hashing the string:
symbol=LTCBTC&side=BUY&type=LIMIT&timeInForce=GTC&quantity=1&price=0.1&recvWindow=5000&timestamp=1499827319559
and return:
c8db56825ae71d6d79447849e617115f4a920fa2acdcab2b053c4b2838bd6b71

Daddie@Greeffer MINGW64 /d/Projects/binance-signature (main)
$
```