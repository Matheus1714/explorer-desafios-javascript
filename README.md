# Desafio - Iniciando com JavaScript

Este é um repositório que resolve desafio simples de Javascript passados no programa Explorer de JavaScript da Rocketseat.

Todos os desafios são resolvidos no arquivo `main.js`.

```js
// main.js
// 1. Crie um script que exiba a mensagem "Hello World!" em um alerta no navegador.
alert('Hello World')

// 2. Crie um script que declare duas variáveis e exiba o resultado da soma entre elas.
const a = 1;
const b = 2;
console.log(a+b)

// 3. Crie um script que declare uma variável e verifique se o seu valor é um número.
// Se for, exiba a mensagem "É um número", caso contrário, exiba a mensagem "Não é um número".

const c = '';

if(typeof c === 'number'){
    console.log('É um número')
}else{
    console.log('Não é um número')
}

// 4. Crie um script que declare uma variável e verifique se o seu valor é uma string. 
//Se for, exiba a mensagem "É uma string", caso contrário, exiba a mensagem "Não é uma string".

const d = 'minha string'

if(typeof c === 'string'){
    console.log('É uma string')
}else{
    console.log('Não é uma string')
}

// 5. Crie um script que declare uma variável e verifique se o seu valor é um booleano.
// Se for, exiba a mensagem "É um booleano", caso contrário, exiba a mensagem "Não é um booleano".

const e = false

if(typeof e === 'boolean'){
    console.log('É um booleano')
}else{
    console.log('Não é um booleano')
}

// 6. Crie um script que declare duas variáveis e exiba o resultado da subtração entre elas.

const f = 1;
const g = 2;
console.log(a-b)

// 7. Crie um script que declare duas variáveis e exiba o resultado da multiplicação entre elas.

const h = 1;
const i = 2;
console.log(h-i)

// 8. Crie um script que declare duas variáveis e exiba o resultado da divisão entre elas.

const j = 1;
const k = 2;
console.log(j/k)

// 9. Crie um script que declare uma variável e verifique se o seu valor é um número par. 
// Se for, exiba a mensagem "É um número par", caso contrário, exiba a mensagem "Não é um número par".

const l = 12;

if (!!(l%2)){
    console.log('É um número par')
}else{
    console.log('Não é um número par')
}

// 10. Crie um script que declare uma variável e verifique se o seu valor é um número ímpar. 
// Se for, exiba a mensagem "É um número ímpar", caso contrário, exiba a mensagem "Não é um número ímpar".

const m = 12;

if (!!(m%2)){
    console.log('Não é um número ímpar')
}else{
    console.log('É um número ímpar')
}
```