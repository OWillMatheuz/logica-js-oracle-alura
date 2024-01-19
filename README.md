# logica-js-oracle-alura
Exercícios do curso Oracle Next Education + Alura 

//1. Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.
```js
console.log("Bem-vindo(a)");
```
//2. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.
```js
let nome = "Willian";
console.log(`Olá, ${nome}!`);
```
//3. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" .
```js
let nomeCompleto = "Willian Matheus";
alert(`Olá, ${nomeCompleto}`);
```
//4. Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.
```js
let pergunta = prompt("Qual a linguagem de programção que você mais gosta?");
console.log(`${pergunta}`);
```
//5. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.
```js
let valor1 = 20;
let valor2 = 30;
let resultado1 = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado1}`);
```
//6. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.
```js
let valor10 = 30;
let valor20 = 20;
let resultado2 = valor10 - valor20;

console.log(
  `A diferença entre ${valor10} e ${valor20} é igual a ${resultado2}`
);
```
//7. Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.
```js
let idade = prompt("Insira sua idade: ");

if (idade >= 18) {
  alert("Ok, você é maior de idade!");
} else {
  alert("Você não é maior de idade!");
}
```
//8. Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.
```js
let numero = prompt("Digita um número, por favor: ");

if (numero > 0) {
  alert("Número é positivo!");
} else if (numero < 0) {
  alert("Este número é negativo!");
} else {
  alert("Este número é 0 ");
}
```
//9. Use um loop while para imprimir os números de 1 a 10 no console.
```js
let contador = 1;

while (contador <= 10) {
  console.log(contador);
  contador++;
}
```
//10. Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.
```js
let nota = 8;

if (nota >= 7) {
  console.log("Aprovado");
} else {
  console.log("Reprovado");
}
```
//11. Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.
```js
let numeroAleatorio = Math.random();
console.log("Número aleatório:", numeroAleatorio);
```

//12. Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.
```js
let numeroQualquer = parseInt(Math.random() * 10 + 1);
console.log("Número aleatório:", numeroQualquer);
```

//13. Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.
```
js
let numeroInt = parseInt(Math.random() * 100 + 1);
console.log("Número aleatório:", numeroInt);
```
