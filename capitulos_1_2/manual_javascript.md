# JavaScript sin vueltas

## Lo basico, basico, basico, basico…
## que tenes que saber de Javascript


### Indice de Capítulos:

1. ¿Qué es JavaScript?
    
    * ¿Dónde se utiliza?

    * Configuración del entorno de desarrollo

2. Fundamentos de JavaScript

    * Variables y tipos de datos

    * Operadores aritméticos y de comparación

    * Estructuras de control de flujo (if/else, switch, while, for)

    * Funciones y objetos en JavaScript

3. Funciones y objetos en JavaScript

    * Funciones y sus parámetros

    * Objetos y propiedades

    * Métodos y eventos

    * Trabajando con el DOM

4. Manipulación de datos con JavaScript

    * Arrays y matrices

    * Objetos JSON

    * Funciones para manipulación de cadenas de texto

    * AJAX y Asincronismo

5. Introducción a frameworks de JavaScript

    * jQuery

    * React.js

    * Vue.js

6. Introducción a Node.js

    * ¿Qué es Node.js?

    * Creación de un servidor web básico con Node.js

    * Manejo de módulos en Node.js

9. Prácticas y ejercicios
    * Proyectos prácticos para aplicar los conocimientos adquiridos

    * Resolución de problemas con JavaScript



## Capítulo 1

### Introducción a JavaScript

JavaScript es un lenguaje de programación utilizado para crear sitios web interactivos y dinámicos. Es uno de los lenguajes más populares y se utiliza en casi todas las páginas web modernas. Es un lenguaje interpretado, lo que significa que no necesita ser compilado antes de ser ejecutado.
JavaScript se utiliza en muchos lugares diferentes, desde la creación de sitios web hasta la creación de aplicaciones móviles y de escritorio. También se utiliza en la programación del lado del servidor a través de Node.js.
Antes de comenzar a programar en JavaScript, es importante configurar el entorno de desarrollo. Esto incluye la instalación de un editor de código y la configuración de un servidor local para la visualización de la página web.
Los fundamentos de JavaScript incluyen variables y tipos de datos, operadores aritméticos y de comparación, estructuras de control de flujo como if/else, switch, while y for, funciones y objetos.
Las variables en JavaScript son contenedores de información y los tipos de datos incluyen números, cadenas, booleanos, arrays y objetos. Los operadores aritméticos y de comparación se utilizan para realizar cálculos y comparaciones entre variables.
Las estructuras de control de flujo, como if/else, switch, while y for, se utilizan para controlar el flujo de ejecución del código. Las funciones son bloques de código reutilizables que pueden aceptar parámetros y devolver valores.
Los objetos en JavaScript son colecciones de propiedades, y los métodos son funciones que se pueden llamar en un objeto. El Document Object Model (DOM) es una representación de la estructura de un documento HTML, y se puede manipular con JavaScript.
La manipulación de datos en JavaScript incluye el trabajo con arrays y matrices, objetos JSON y funciones para manipulación de cadenas de texto. AJAX se utiliza para hacer solicitudes asincrónicas al servidor y actualizar la página web sin necesidad de recargarla.
Introducimos algunos frameworks de JavaScript como jQuery, React.js y Vue.js, y también exploramos Node.js, un entorno de ejecución del lado del servidor para JavaScript.
Para poner en práctica los conocimientos adquiridos, se incluyen proyectos prácticos y ejercicios de resolución de problemas. Estos proyectos ayudan a aplicar los conceptos de JavaScript en un contexto real y a desarrollar habilidades de resolución de problemas.


Capitulo 2:

Variables y tipos de datos

En JavaScript, una variable es un contenedor que almacena un valor que puede ser de diferentes tipos de datos. Los tipos de datos son la forma en que se clasifican y se manejan diferentes tipos de valores en un programa.

En JavaScript, hay varios tipos de datos, que incluyen:

Números: los números son valores numéricos, como 1, 2, 3.14159, etc. En JavaScript, los números pueden ser enteros o decimales, y se pueden realizar operaciones matemáticas con ellos.

Cadenas: las cadenas son secuencias de caracteres, como "Hola" o "JavaScript". En JavaScript, las cadenas se pueden concatenar (unir) y se pueden realizar diferentes operaciones de manipulación de cadenas.

Booleanos: los booleanos son valores que son verdaderos o falsos. En JavaScript, los booleanos se utilizan a menudo en las sentencias condicionales para tomar decisiones en función de si una condición es verdadera o falsa.

Nulos: el valor nulo representa la ausencia de un valor. En JavaScript, si una variable se establece en null, significa que no tiene ningún valor.

Indefinidos: el valor indefinido se utiliza para representar una variable que no ha sido asignada o que no tiene ningún valor.

Objetos: los objetos son valores que contienen múltiples propiedades y métodos. En JavaScript, los objetos se utilizan para representar cosas del mundo real, como un usuario de un sitio web o un producto en una tienda en línea.

Arreglos: los arreglos son valores que contienen múltiples elementos, que se pueden acceder mediante un índice numérico. En JavaScript, los arreglos se utilizan para almacenar colecciones de datos relacionados.

Para declarar una variable en JavaScript, se utiliza la palabra clave var, let o const, seguida del nombre de la variable y opcionalmente se le asigna un valor. Por ejemplo:

``` javascript
Copy code
var numero = 42; // se declara una variable llamada numero y se le asigna el valor 42
let cadena = "Hola"; // se declara una variable llamada cadena y se le asigna el valor "Hola"
const PI = 3.14159; // se declara una constante llamada PI y se le asigna el valor 3.14159

```

Es importante tener en cuenta que var y let permiten cambiar el valor de la variable después de su declaración, mientras que const no permite reasignar la variable después de su inicialización.


## Operadores Aritmeticos


En JavaScript, los operadores aritméticos y de comparación son herramientas fundamentales para realizar operaciones matemáticas y comparar valores en programas. A continuación, te proporcionaré una explicación breve sobre cada uno de ellos y algunos ejemplos de código para que puedas entender mejor su uso:

## Operadores Aritméticos

Los operadores aritméticos son utilizados para realizar operaciones matemáticas básicas. En JavaScript, se pueden utilizar los siguientes operadores aritméticos:

## Suma (+)
El operador de suma (+) se utiliza para sumar dos valores.

Ejemplo de código:

``` javascript
let a = 5;
let b = 10;
let resultado = a + b; // El valor de resultado será 15
```
## Resta (-)
El operador de resta (-) se utiliza para restar dos valores.

Ejemplo de código:

``` javascript
let a = 5;
let b = 10;
let resultado = b - a; // El valor de resultado será 5
```

## Multiplicación (*)
El operador de multiplicación (*) se utiliza para multiplicar dos valores.

Ejemplo de código:

``` javascript
let a = 5;
let b = 10;
let resultado = a * b; // El valor de resultado será 50
```
## División (/)
El operador de división (/) se utiliza para dividir dos valores.

Ejemplo de código:

``` javascript
let a = 5;
let b = 10;
let resultado = b / a; // El valor de resultado será 2
```
## Módulo (%)
El operador de módulo (%) se utiliza para obtener el resto de una división.

Ejemplo de código:

``` javascript
let a = 5;
let b = 10;
let resultado = b % a; // El valor de resultado será 0
```
## Operadores de Comparación
Los operadores de comparación se utilizan para comparar dos valores. En JavaScript, se pueden utilizar los siguientes operadores de comparación:

## Igualdad (==)
El operador de igualdad (==) se utiliza para comparar si dos valores son iguales.

Ejemplo de código:

``` javascript
let a = 5;
let b = "5";
if (a == b) {
  console.log("Los valores son iguales");
} else {
  console.log("Los valores son diferentes");
}
// La salida será "Los valores son iguales"
```
## Igualdad Estricta (===)
El operador de igualdad estricta (===) se utiliza para comparar si dos valores son iguales y del mismo tipo.

Ejemplo de código:

```javascript

let a = 5;
let b = "5";
if (a === b) {
  console.log("Los valores son iguales");
} else {
  console.log("Los valores son diferentes");
}
// La salida será "Los valores son diferentes"
```
## Desigualdad (!=)
El operador de desigualdad (!=) se utiliza para comparar si dos valores son diferentes.

Ejemplo de código:

```javascript

let a = 5;
let b = 10;
if (a != b) {
  console.log("Los valores son diferentes");
} else {
  console.log("Los valores son iguales");
}
// La salida será "Los valores son diferentes"
```

## Desigualdad Estricta (!==)
El operador de desigualdad estricta (!==) se utiliza para comparar si dos valores son diferentes y del mismo tipo.

Ejemplo de código:

``` javascript

let a = 5;
let b = "5";
if (a !== b) {
  console.log("Los valores son diferentes y del mismo tipo");
} else {
  console.log("Los valores son iguales o del mismo tipo");
}
// La salida será "Los valores son diferentes y del mismo tipo"
```
## Mayor que (>)
El operador mayor que (>) se utiliza para comparar si el primer valor es mayor que el segundo.

Ejemplo de código:

``` javascript
let a = 10;
let b = 5;
if (a > b) {
  console.log("a es mayor que b");
} else {
  console.log("a es menor o igual que b");
}
// La salida será "a es mayor que b"
```
## Menor que (<)
El operador menor que (<) se utiliza para comparar si el primer valor es menor que el segundo.

Ejemplo de código:

``` javascript
let a = 10;
let b = 5;
if (a < b) {
  console.log("a es menor que b");
} else {
  console.log("a es mayor o igual que b");
}
// La salida será "a es mayor o igual que b"

```

## Mayor o igual que (>=)
El operador mayor o igual que (>=) se utiliza para comparar si el primer valor es mayor o igual que el segundo.

Ejemplo de código:

``` javascript 
let a = 10;
let b = 5;
if (a >= b) {
  console.log("a es mayor o igual que b");
} else {
  console.log("a es menor que b");
}
// La salida será "a es mayor o igual que b"
```
## Menor o igual que (<=)
El operador menor o igual que (<=) se utiliza para comparar si el primer valor es menor o igual que el segundo.

Ejemplo de código:

``` javascript
let a = 10;
let b = 5;
if (a <= b) {
  console.log("a es menor o igual que b");
} else {
  console.log("a es mayor que b");
}
// La salida será "a es mayor que b"

``` 