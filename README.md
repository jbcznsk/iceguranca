# iceguranca
desculpa pelo nome

## Logs
As coletas dos logs foram feitas com a ferramenta <b> strace </b> através do comando
```
strace -t -f -o <OUTPUT_FILE.txt> <PROGRAMA>
```

## Cryptojacking
Para testar o cryptojacking, foi feita uma conta no site [CoinImp](https://www.coinimp.com/). O código de mining foi botado no index.html localizado no /var/www/. Para testar no localhost foi iniciado um server no Apache2 com o comando ```sudo service apache2 start```.
