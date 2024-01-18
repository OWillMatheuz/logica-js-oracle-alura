# logica-js-oracle-alura
Exercícios do curso Oracle Next Education + Alura 

1. Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.
```js
let contador = 1;

while (contador <= 10) {
    console.log(contador);
    contador++;
}
```
2. Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```js
let contador = 10;

while (contador >= 0) {
    console.log(contador);
    contador--;
}
```
3. Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```js
let numeroInicial = prompt("Digite um número para a contagem regressiva:"));

while (numeroInicial >= 0) {
    console.log(numeroInicial);
    numeroInicial--;
}
```
4. Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```js
let numeroFinal = prompt("Digite um número para a contagem progressiva:"));
let contador = 0;

while (contador <= numeroFinal) {
    console.log(contador);
    contador++;
}
```
