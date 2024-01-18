# logica-js-oracle-alura
Exercícios do curso Oracle Next Education + Alura 

// 1° Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".
```js
let diaDaSemana = prompt("Qual é o dia da semana?");
```
// Verifique se a resposta é "sábado" ou "domingo" e exiba a mensagem apropriada
// Usei o toLowerCase para que quando o usuario digitar Maiuscula ou minuscula, o js entenda e não de resposta errada!
```js
diaDaSemana = diaDaSemana.toLowerCase();
if (diaDaSemana == "sabado" || diaDaSemana == "domingo") {
  alert("Bom fim de semana!");
} else {
  alert("Boa semana!");
}
```
// 2° Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
```js
let numero = prompt("Digite um número:");
// Verificar se o número é positivo ou negativo
```js
if (numero >= 0) {
  alert("O número é positivo!");
} else {
  numero <= 0;
  alert("O número é negativo!");
}
```
// 3° Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
```js
let pontos = prompt("Digite sua pontuação:");
```
// Verificar se a pontuação é maior ou igual a 100
```js
if (pontos >= 100) {
  alert("Parabéns, você venceu!");
} else {
  alert("Tente novamente para ganhar.");
}
```
// 4° Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
```js
let saldo = 800;
```
// usei dois tipos strings, o primeiro concatenação e o segundo tempalte strings
```js
let mensagem = "O saldo da sua conta é R$" + saldo;
let mensagemSaldo = `O saldo da sua conta é R$ ${saldo}`;

alert(mensagem);
alert(mensagemSaldo);
```
// 5° Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
```js
let nome = prompt("Digite o seu nome: ");
alert("Boas vindas ao desenvolvedor front-end " + nome);
```
