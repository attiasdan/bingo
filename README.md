# Bingo
Este script consiste em uma lógica JavaScript para simular um jogo de **Bingo**.

## Configurações
No arquivo `Bingo.html` ajuste as seguintes configurações
```javascript
var totalNumeros = 100; // QUANTIDADE DE NÚMEROS QUE PODEM SER SORTEADOS
var cartela = []; // CONTROLE DE NÚMEROS NÃO SORTEADOS
var nroSorteados = []; // CONTROLE DE NÚMEROS SORTEADOS
var totalSorteados = 0; // CONTROLE DO FIM DO JOGO
var sorteados = ""; // AUXILIAR DE EXIBIÇÃO
```
## Executando
Abra o arquivo `Bingo.html` em um navegador e pressione a tecla `ESPAÇO`, assim o _loader_ será acionado enquanto um número aleatório é escolhido, após isso o _loader_ é finalizado, o número escolhido é mostrado em destaque e adicionado na lista de números sorteados.
