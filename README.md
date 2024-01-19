# logica-js-oracle-alura
Exercícios do curso Oracle Next Education + Alura 

//1. Criar uma função que exibe "Olá, mundo!" no console.
```js
function olaMundo() {
  console.log("Olá, mundo!");
}
olaMundo();
```
//2. Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
```js
function saudacao(nome) {
  console.log("Olá, " + nome + "!");
}
saudacao("Will Matheus");
```
//3. Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
```js
function vezes(numero) {
  return numero * 2;
}
let resul = vezes(10);
console.log(resul);
```
//4. Criar uma função que recebe três números como parâmetros e retorna a média deles.
```js
function media(numero1, numero2, numero3) {
  var soma = numero1 + numero2 + numero3;
  var media = soma / 3;
  return media;
}
let resultado = media(7, 7, 8);
console.log(resultado);
```
//5. Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
```js
function maiorNumero(num1, num2) {
  return Math.max(num1, num2);
}
let resultado1 = maiorNumero(25, 35);
console.log(resultado1);
```
//6. Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo
```js
function eleMesmo(number) {
  return number * number;
}
let resultado2 = eleMesmo(4);
console.log(resultado2);
```
