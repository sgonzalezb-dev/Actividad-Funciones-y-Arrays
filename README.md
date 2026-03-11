En JavaScript, los arrays tienen funciones preestablecidas (métodos) que permiten manipular sus elementos fácilmente. Aquí tienes 7 de las más usadas:

1️⃣ push()

Sirve para agregar un elemento al final del array.

let numeros = [1,2,3]

numeros.push(4)

console.log(numeros)

Resultado:

[1,2,3,4]
2️⃣ pop()

Sirve para eliminar el último elemento del array.

let numeros = [1,2,3]

numeros.pop()

console.log(numeros)

Resultado:

[1,2]
3️⃣ shift()

Sirve para eliminar el primer elemento del array.

let numeros = [1,2,3]

numeros.shift()

console.log(numeros)

Resultado:

[2,3]
4️⃣ unshift()

Sirve para agregar elementos al inicio del array.

let numeros = [2,3]

numeros.unshift(1)

console.log(numeros)

Resultado:

[1,2,3]
5️⃣ length

Sirve para saber cuántos elementos tiene el array.

let frutas = ["manzana","pera","uva"]

console.log(frutas.length)

Resultado:

3
6️⃣ indexOf()

Sirve para buscar la posición de un elemento.

let frutas = ["manzana","pera","uva"]

console.log(frutas.indexOf("pera"))

Resultado:
1
(porque empieza a contar desde 0)

7️⃣ includes()

Sirve para verificar si un elemento existe en el array.

let frutas = ["manzana","pera","uva"]
console.log(frutas.includes("pera"))
Resultado:
true
Las funciones flecha (arrow functions) son una forma más corta y moderna de escribir funciones en JavaScript. Se usan mucho hoy en día porque el código queda más limpio y fácil de leer.

La sintaxis usa el símbolo:

=>
1️⃣ Función normal
function sumar(a,b){
    return a + b;
}
Función flecha equivalente
const sumar = (a,b) => {
    return a + b;
}
2️⃣ Forma más corta (cuando solo hay una línea)

Si la función solo devuelve algo, se puede escribir así:

const sumar = (a,b) => a + b;
3️⃣ Ejemplo básico
const multiplicar = (a,b) => a * b;

console.log(multiplicar(4,5));

Resultado:

20
4️⃣ Función flecha con un solo parámetro

Si solo hay un parámetro, los paréntesis son opcionales.

const cuadrado = n => n * n;

console.log(cuadrado(6));

Resultado:

36
5️⃣ Función flecha sin parámetros

Si no recibe parámetros, se usan paréntesis vacíos.

const saludar = () => {
    console.log("Hola");
}

saludar();
6️⃣ Ejemplo con arrays
let numeros = [1,2,3,4]

numeros.forEach(n => {
    console.log(n);
})

Resultado:

1
2
3
4
7️⃣ Comparación rápida
Función normal	Función flecha
function sumar(a,b){ return a+b }	(a,b) => a + b
más larga	más corta
estilo clásico	estilo moderno
