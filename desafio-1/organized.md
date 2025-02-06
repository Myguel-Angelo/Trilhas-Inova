## Questões organizados pra vizualisação

#### 1° Crie uma variável chamada nome e atribua seu nome a ela. Em seguida, exiba o valor dessa variável.
```js
let nome = 'Myguel Ângelo';
console.log(nome);
```

#### 2° Crie duas variáveis: uma chamada idade e outra chamada altura. Atribua a idade o valor 25 e a altura o valor 1.75. Exiba ambos os valores.
```js
let idade = 25;
let altura = 1.75;
console.log(idade, altura);
```

#### 3° Crie uma variável chamada preco com o valor 50 e uma variável desconto com o valor 0.2 (20%). Calcule o preço com desconto e exiba o valor final.
```js
let preco = 50;
let desconto = 0.2;
let valorComDesconto = preco-(preco*desconto);
console.log(valorComDesconto);
```

#### 4° Crie uma variável chamada temperatura e atribua o valor 30. Se a temperatura for maior que 25, exiba a mensagem "Está calor!". Caso contrário, exiba "Está fresco!".
```js
let temperatura = 30;  
if (temperatura > 25) {  
    console.log("Está calor!");  
} else {  
    console.log("Está fresco!");  
}  
```

#### 5° Crie uma variável idade e atribua um valor. Se a pessoa for maior de idade (18 ou mais), exiba "Você é maior de idade". Caso contrário, exiba "Você é menor de idade".
```js
let idade = 18;  // Eu tenho 18 kkkkk
if (idade >= 18) {  
    console.log("Você é maior de idade");  
} else {  
    console.log("Você é menor de idade");  
} 
```

#### 6° Crie uma variável chamada nota e atribua um valor entre 0 e 10. Se a nota for maior ou igual a 7, exiba "Aprovado". Se for entre 5 e 6, exiba "Recuperação". Caso contrário, exiba "Reprovado".
```js
let nota = 6;  /// Em homenagem a questão 6
if (nota >= 7) {  
    console.log("Aprovado");  
} else if (nota >= 5) {  
    console.log("Recuperação");  
} else {  
    console.log("Reprovado");  
} 
```

#### 7° Crie duas variáveis, numero1 e numero2, e atribua valores a elas. Verifique se os dois números são iguais e, caso sejam, exiba "Os números são iguais". Caso contrário, exiba "Os números são diferentes".
```js
let numero1 = 10;  
let numero2 = 20;  
if (numero1 == numero2) {  
    console.log("Os números são iguais");  
} else {  
    console.log("Os números são diferentes");  
} 
```

#### 8° Crie uma variável chamada nome e uma variável chamada idade. Exiba a mensagem "Olá, meu nome é [nome] e eu tenho [idade] anos", utilizando concatenação.
```js
let nome = "Ângelo Nunes";  
let idade = 18;  
console.log("Olá, meu nome é " + nome + " e eu tenho " + idade + " anos");
```

#### 9° Crie um loop que imprima os números de 1 a 10 na tela.
```js
let cont = 1;
while(cont<=10) {
    console.log(cont);
    cont++;
}
```

#### 10° Crie um loop que peça ao usuário para digitar um número até que ele digite o número 5.
```js
let numero = prompt("Digite um número:");
while(numero!=5) {
    console.log(numero);
    numero = prompt("Digite um número:");  
}  
console.log("Você digitou 5, encerrando...");  
```

#### 11° Crie um loop que imprima a tabuada do número 7, de 1 a 10.
```js
let multi = 0;
let number = 7;
while(multi<=10){
    console.log(`${number} x ${multi} =`, multi*number);
    multi++;
}
```

#### 12° Crie um loop que exiba todos os números pares de 0 a 20.
```js
let number = 0;
while(number<=20){
    console.log(number);
    number+=2;
}
```

#### 13° Escreva um código que calcule a área de um círculo. Utilize uma função para realizar o cálculo. A função deve receber o raio como parâmetro e retornar a área.
```js
function calcularAreaCirculo(raio) {  
    return Math.PI * (raio**2); 
    //Pensei em usar 3.14, mas achei esse Math.PI na net e resulvi usar
}  
console.log(calcularAreaCirculo(5)); 
```

#### 14° Comente seu código explicando o que cada parte faz. Crie um programa simples que calcule a soma de dois números e imprima o resultado.
```js
// Função para somar dois números (A e B)  
function somar(a, b) {  
    return a + b; // retorna a soma de a+b
}  
let resultado = somar(14, 41);  //variável que recebe o retorno da função
console.log(resultado);  // Exibindo o resultado
```

#### 15° Refatore o código abaixo para que seja mais legível, usando boas práticas de nomenclatura e separando o código em funções:

```
x=10
y = 20
z = x+y
console.log(z)
```
| Solução:
```js
function somarNumeros(x, y) {  
    return x + y;  
}  
let x = 15;
let y = 51;
let z = somarNumeros(x, y);  
console.log(z);  
```
