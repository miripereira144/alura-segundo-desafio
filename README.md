# aluraSegundoDesafio
logica de programacion 
# Resolución del desafío 2

Saber cómo usar funciones es uno de los conceptos fundamentales en la programación y el desarrollo de software. Las funciones desempeñan un papel crucial en la organización, modularización y reutilización del código.



1. Crear una función que muestra "¡Hola, mundo!" en la consola.




2. Crear una función que recibe un nombre como parámetro y muestra "¡Hola, [nombre]!" en la consola.



3. Crear una función que recibe un número como parámetro y devuelve el doble de ese número.






resolucion =

function mostrarHola() {
    console.log("¡Hola, mundo!");
}

function mostrarHolaNombre(nombre) {
    console.log(`¡Hola, ${nombre}!`);
}

function calcularDoble(numero) {
    return numero * 2;
}

function calcularPromedio(a, b, c) {
    return (a + b + c) / 3;
}

function encontrarMayor(a, b) {
    return a > b ? a : b;
}

function cuadrado(numero) {
    return numero * numero;
}

function mostrarHolaNombreHTML() {
    let nombre = document.getElementById("nombre").value;
    alert(`¡Hola, ${nombre}!`);
}

function calcularDobleHTML() {
    let numero = document.getElementById("numeroDoble").value;
    alert(calcularDoble(numero));
}

function calcularPromedioHTML() {
    let num1 = parseFloat(document.getElementById("num1").value);
    let num2 = parseFloat(document.getElementById("num2").value);
    let num3 = parseFloat(document.getElementById("num3").value);
    alert(calcularPromedio(num1, num2, num3));
}

function encontrarMayorHTML() {
    let num1 = parseFloat(document.getElementById("numMayor1").value);
    let num2 = parseFloat(document.getElementById("numMayor2").value);
    alert(encontrarMayor(num1, num2));
}

function cuadradoHTML() {
    let numero = document.getElementById("numeroCuadrado").value;
    alert(cuadrado(numero));
}




4. Crear una función que recibe tres números como parámetros y devuelve su promedio.



5. Crear una función que recibe dos números como parámetros y devuelve el mayor de ellos.


6. Crear una función que recibe un número como parámetro y devuelve el resultado de multiplicar ese número por sí mismo.

