---
date: 2025-08-31
---

# Introducción a JavaScript y su ejecución en navegadores

## definición

JavaScript es un lenguaje de programación esencial en el desarrollo web moderno.  
Su capacidad para ejecutarse directamente en navegadores permite la creación de páginas dinámicas e interactivas que transforman la experiencia del usuario.

JavaScript nació en 1995 por iniciativa de Brendan Eich en Netscape, con el objetivo de proporcionar interactividad a las páginas web estáticas. Actualmente, se ha convertido en el **lenguaje universal de la web**, presente en todos los navegadores y normalizado por la especificación **ECMAScript (ECMA-262)**.

## Ejecución en navegadores

A diferencia de los lenguajes compilados, **JavaScript se interpreta directamente en el navegador** mediante un motor interno, lo que permite ejecutar instrucciones en tiempo real mientras el usuario navega. Este enfoque posibilita que las páginas reaccionen a eventos del usuario sin necesidad de recargar todo el documento.

## Motores de JavaScript

Cada navegador cuenta con su propio motor, encargado de interpretar y ejecutar el código. Los principales son:

## Proceso de ejecución

El motor de JavaScript realiza tres etapas principales:
1. **Parsing:** Análisis del código fuente para convertirlo en un árbol de sintaxis.  
2. **Compilación Just-In-Time (JIT):** Traducción del código a instrucciones de máquina optimizadas.  
3. **Ejecución:** Interpretación línea por línea y manipulación del **DOM (Document Object Model)**.

## Ejemplo de integración en HTML

```html
``​`html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo JavaScript</title>
</head>
<body>
  <h1>Bienvenido</h1>
  <p id="mensaje"></p>

  <script>
    document.getElementById("mensaje").innerText = "Este texto fue generado con JavaScript";
  </script>
</body>
</html>
```

# Variables y tipos de datos en JavaScript

Las variables son espacios de memoria destinados a almacenar datos que serán utilizados en la ejecución del programa. En JavaScript pueden declararse de tres maneras:

var: declaración tradicional (menos recomendada por problemas de alcance).

let: permite variables de alcance limitado (bloque o función).

const: define constantes cuyo valor no puede reasignarse.

## Ejemplo de declaración:

```javascript
let nombre = "Ana";      // String
const edad = 21;         // Number
var estudiante = true;   // Boolean

```

## Tipos de datos primitivos:

## String (cadenas de texto):

```javascript
let saludo = "Hola Mundo";

```

## Number (números enteros y decimales):

```javascript
let pi = 3.1416;
```

## Boolean (verdadero/falso):

```javascript
let activo = false;

```

## Undefined (sin valor asignado):

```javascript
let x;
console.log(x); // undefined

```

## Null (ausencia de valor):

```javascript
let y = null;
```

## Symbol (identificadores únicos):

```javascript
let id = Symbol("clave");
```

## BigInt (números enteros muy grandes):

```javascript
let big = 9007199254740991n;

```

## Tipos de datos estructurados (objetos):

Array: Colecciones ordenadas.

```javascript
let colores = ["rojo", "verde", "azul"];

```

Object: Estructuras clave-valor.

```javascript
let persona = {
  nombre: "Carlos",
  edad: 30,
  estudiante: true
};

```

El dominio correcto de variables y tipos de datos permite organizar, procesar y manipular información de manera eficiente, constituyendo la base de todo desarrollo en JavaScript.
