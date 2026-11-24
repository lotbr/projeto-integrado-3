# projeto-integrado-3

https://www.udemy.com/course/32-conceitos-todo-dev-javascript-deveria-saber/learn/lecture/17666258#overview
PILHAS DE CAMADAS

FIFO first in first out = Oprimeiro que entrou e o primeiro a sair
LIFO last in first out = o ultimo  que entra e o primeiro que sai

function funcaol () {
funcao2();
console.log('executou função 1');
}

function funcao2 () {
funcao3();
console.log('executou função 1');
}

function funcao3 () {
console.log('executou função 3');
}

funcao1();


TIPOS PRIMITIVOS

console.log(typeof true); // boolean
console.log(typeof boolean(true)); // boolean
console.log(typeof new boolean(true)); // boolean
console.log(typeof (new bolean(true)).valueOf()); // boolean

var doze = new number (12);
var quinze = doze + 3;

console.log (quinze); = 15

console.log(typeof quinze);

tipos de valores e tipos de referencias
