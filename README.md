<h1 align="center">UNIVERSIDAD NACIONAL DEL CENTRO DEL PERÚ</h1>

<div align="center">   
    <img width="400" height="350" src="https://upload.wikimedia.org/wikipedia/commons/9/92/Escudo_UNCP.png" />
</div>

<h2 align="center">
    <p>FACULTAD DE INGENIERÍA DE SISTEMAS</p>
    <p>DESARROLLO DE APLICACIONES WEB</p>
</h2>

<h2 align="center">
     Conocimientos avanzados del lenguaje de diseño CSS
</h2>

**PRESENTADO POR:**

◼️Aranda Gomez Zarella Andrea

◼️Huaman Rojas Jhordan Armando

◼️Macha Pariona Angel Yoelver

◼️Mallqui Meza Jhamir Edu

◼️Quispe Ortiz Jhosep 

<h2 align="center">
    <p>HUANCAYO -- PERÚ</p>
    <p>2025</p>
</h2>

---

# ÍNDICE


[ÍNDICE]

[INTRODUCCIÓN]

[CAPITULO 1 - Introducción a JavaScript y su ejecución en navegadores]

[CAPITULO 2 - Variables y tipos de datos (String, Number, Boolean, Arrays, Objects)]

[CAPITULO 3 - Operadores (aritméticos, lógicos, comparación)]

[CAPITULO 4 - Condicionales (if, else, switch)]

[CAPITULO 5 - Bucles (for, while, do while) ]

[CAPITULO 6 - Funciones (declaración, expresiones, parámetros, retorno)]

[CAPITULO 7 - Manipulación del DOM (seleccionar elementos, modificar contenido, eventos)]

[CAPITULO 8 - Eventos y manejadores (addEventListener, onclick, etc.)]

[CAPITULO 9 - JSON y almacenamiento local (localStorage, sessionStorage)]

[CAPITULO 10 - Depuración y uso de la consola (console.log, debugger)]

[CONCLUSIÓN]

[REFERENCIA BIBLIOGRÁFICA]

# INTRODUCCIÓN

La siguiente monografía profundiza el tema del lenguaje de diseño CSS,
conocido como Cascading Style Sheets, la cual aplicar estilos a
documentos, en su mayoría documentos HTML. Este lenguaje permite que la
información de los documentos HTML tenga un aspecto que sea organizado,
llamativo e interesante para los usuarios añadiendo el diseño de los
bloques, los colores de las letras o fondos de los bloques, las formas
que pueden tomar algunos bloques, entre otras funciones (Manz, s. f.).
Por la funcionalidad que tiene este lenguaje, es muy importante para un
desarrollador de páginas web el tener conocimientos sobre CSS al ser un
tema fundamental para las páginas web.

Por lo tanto, se tiene como objetivo el conocer temas más avanzados
relacionados con CSS. Para ello se buscará información de fuentes
fiables para los temas seleccionados que se mostrarán en los capítulos
para luego mostrar ejemplos aplicables de los temas utilizando códigos y
sus resultados.

Esta investigación resulta pertinente debido al aumento de la
importancia de las páginas web en la actualidad, ya que para las
organizaciones al intentar captar la atención de los usuarios buscan que
su página web, aparte que tenga la información relevante sobre ellos,
también buscan que sea llamativo, atractivo y tenga una buena
optimización de rendimiento, por lo cual beneficia a las organizaciones
utilizar CSS. También es importante para el aspecto académico, ya que,
al ser importante para las organizaciones, es muy demandado por el
mercado laboral, la cual servirá para los front-end, diseñadores
gráficos y especialistas en experiencia de usuario.

El tipo de esta investigación será de Investigación documental y
descriptiva, ya que se buscará información revisando documentos,
artículos, cursos y recursos web especializados. también es exploratoria
ya que busca profundizar en temas avanzas relacionados con CSS.

# CAPITULO 1 - Introducción a JavaScript y su ejecución en navegadores

## definición
A diferencia de los lenguajes compilados, JavaScript se interpreta directamente en el navegador mediante un motor interno, lo que permite ejecutar instrucciones en tiempo real mientras el usuario navega. Este enfoque posibilita que las páginas reaccionen a eventos del usuario sin necesidad de recargar todo el documento.

## Motores de JavaScript

Cada navegador cuenta con su propio motor, encargado de interpretar y ejecutar el código. Los principales son:

## Proceso de ejecución

El motor de JavaScript realiza tres etapas principales:
1. Parsing: Análisis del código fuente para convertirlo en un árbol de sintaxis.  
2. Compilación Just-In-Time (JIT): Traducción del código a instrucciones de máquina optimizadas.  
3. Ejecución: Interpretación línea por línea y manipulación del DOM (Document Object Model).

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

# CAPITULO 2 - Variables y tipos de datos en JavaScript

Las variables son espacios de memoria destinados a almacenar datos que serán utilizados en la ejecución del programa. En JavaScript pueden declararse de tres maneras:
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

# CAPITULO 3 - Teoría de Operadores en JavaScript

En JavaScript, los **operadores** permiten realizar operaciones sobre valores y variables. 
A continuación se describen los principales tipos de operadores: aritméticos, lógicos y de comparación.

---

## 1. Operadores Aritméticos
Se utilizan para realizar operaciones matemáticas.

| Operador | Descripción     | Ejemplo         | Resultado |
|:--------:|-----------------|-----------------|:---------:|
|   `+`    | Suma            | `5 + 3`         | 8         |
|   `-`    | Resta           | `5 - 3`         | 2         |
|   `*`    | Multiplicación  | `5 * 3`         | 15        |
|   `/`    | División        | `6 / 2`         | 3         |
|   `%`    | Módulo (resto)  | `5 % 2`         | 1         |
|   `**`   | Potencia        | `2 ** 3`        | 8         |
|   `++`   | Incremento      | `x = 5; x++`    | 6         |
|   `--`   | Decremento      | `x = 5; x--`    | 4         |

---

## 2. Operadores Lógicos
Se usan para combinar condiciones y devuelven un valor booleano (`true` o `false`).

| Operador | Descripción                                              | Ejemplo                | Resultado |
|:--------:|----------------------------------------------------------|------------------------|:---------:|
| `&&`     | **AND**: verdadero si ambas condiciones son verdaderas   | `(5 > 3) && (8 > 6)`   | true      |
| `||`     | **OR**: verdadero si al menos una condición es verdadera | `(5 > 3) \|\| (8 < 6)` | true      |
| `!`      | **NOT**: invierte el valor lógico                        | `!(5 > 3)`             | false     |

---

## 3. Operadores de Comparación
Comparan valores y devuelven `true` o `false`.

| Operador | Descripción                                  | Ejemplo      | Resultado |
|:--------:|----------------------------------------------|--------------|:---------:|
| `==`     | Igual en valor (comparación débil)           | `5 == "5"`   | true      |
| `===`    | Igual en valor y tipo (comparación estricta) | `5 === "5"`  | false     |
| `!=`     | Diferente en valor                           | `5 != 3`     | true      |
| `!==`    | Diferente en valor o tipo                    | `5 !== "5"`  | true      |
| `>`      | Mayor que                                    | `7 > 5`      | true      |
| `<`      | Menor que                                    | `3 < 5`      | true      |
| `>=`     | Mayor o igual                                | `5 >= 5`     | true      |
| `<=`     | Menor o igual                                | `4 <= 5`     | true      |

---

## Nota sobre `==` y `===`
- `==` compara solo el valor, haciendo conversión de tipo si es necesario.
- `===` compara valor y tipo de dato sin conversión.
- Se recomienda usar `===` para evitar resultados inesperados.

---



# CAPÍTULO 4 – Teoría de Condicionales en JavaScript


Los **condicionales** en JavaScript permiten ejecutar diferentes bloques de código dependiendo de si una condición es verdadera o falsa.  
Son fundamentales para el control del flujo de un programa.

---

## 1. Estructura `if`
El condicional `if` ejecuta un bloque de código solo si la condición es **verdadera** (`true`).  
Si la condición es **falsa** (`false`), el bloque se omite.

**Sintaxis:**
```javascript
if (condicion) {
    // Código que se ejecuta si la condición es verdadera
}
```

**Ejemplo:**
```javascript
let edad = 18;
if (edad >= 18) {
    console.log("Eres mayor de edad");
}
```

---

## 2. Estructura `if...else`
Permite ejecutar un bloque si la condición es verdadera y otro si es falsa.

**Sintaxis:**
```javascript
if (condicion) {
    // Código si la condición es verdadera
} else {
    // Código si la condición es falsa
}
```

**Ejemplo:**
```javascript
let edad = 16;
if (edad >= 18) {
    console.log("Eres mayor de edad");
} else {
    console.log("Eres menor de edad");
}
```

---

## 3. Estructura `if...else if...else`
Se utiliza para evaluar múltiples condiciones en orden.  
El primer bloque cuya condición sea verdadera será ejecutado y los demás serán ignorados.

**Sintaxis:**
```javascript
if (condicion1) {
    // Código si condicion1 es verdadera
} else if (condicion2) {
    // Código si condicion2 es verdadera
} else {
    // Código si ninguna condición anterior es verdadera
}
```

**Ejemplo:**
```javascript
let nota = 15;
if (nota >= 18) {
    console.log("Excelente");
} else if (nota >= 14) {
    console.log("Aprobado");
} else {
    console.log("Reprobado");
}
```

---

## 4. Estructura `switch`
El condicional `switch` evalúa una expresión y la compara contra múltiples **casos**.  
Si encuentra coincidencia, ejecuta el código correspondiente a ese caso.

**Sintaxis:**
```javascript
switch (expresion) {
    case valor1:
        // Código si expresion === valor1
        break;
    case valor2:
        // Código si expresion === valor2
        break;
    default:
        // Código si no coincide con ningún caso
}
```

**Ejemplo:**
```javascript
let dia = 3;
switch (dia) {
    case 1:
        console.log("Lunes");
        break;
    case 2:
        console.log("Martes");
        break;
    case 3:
        console.log("Miércoles");
        break;
    default:
        console.log("Día no válido");
}
```

---

## Comparación y recomendaciones

- **`if`**: Úsalo cuando solo necesites evaluar una condición.
- **`if...else`**: Úsalo cuando haya dos posibles caminos de ejecución.
- **`if...else if...else`**: Úsalo para evaluar varias condiciones secuencialmente.
- **`switch`**: Úsalo cuando una sola variable o expresión deba ser comparada contra varios valores posibles.
- Evita escribir condicionales excesivamente anidados, ya que afectan la legibilidad.
- En `switch`, recuerda incluir `break` en cada caso para evitar la **caída de casos** (*fall-through*).
- Usa comparaciones estrictas (`===`) en vez de las débiles (`==`) para evitar errores de tipo.

---

## Ejemplo combinado
```javascript
let opcion = "B";


```

# CAPÍTULO 5 – Bucles (for, while, do…while)

## for clásico

Sirve para repetir un bloque un número conocido de veces (control por contador: inicialización → condición → actualización).

```javascript
const n = 5;
let suma = 0;
for (let i = 1; i <= n; i++) {
  suma += i;
}
console.log(suma); // 15

```

Variantes útiles


•	for...of: recorre valores de iterables (arrays, strings, Maps, Sets).

•	for...in: recorre claves (propiedades enumerables) —útil para objetos, con cuidado.

```javascript
// for...of (valores)
const nums = [3, 7, 2, 9];
let max = -Infinity;
for (const x of nums) {
  if (x > max) max = x;
}
console.log(max); // 9

// for...in (claves) en objetos
const persona = { nombre: "Ana", edad: 21 };
for (const key in persona) {
  if (Object.hasOwn(persona, key)) { // evita propiedades heredadas
    console.log(key, "→", persona[key]);
  }
}


```

Tip: Para objetos, muchas veces es más claro Object.entries(obj).forEach(([k,v]) => ...)
## Explicación gráfica 
En este ejemplo observaremos un caso sobre como definir una lista de personas y aplicar for ,  for ..of y for ... in
```javascript
var listaPersonas = [
 {"nombre": "pepe", "apellidos": "perez"},
 {"nombre": "ana", "apellidos": "gomez"},
 {"nombre": "almudena", "apellidos": "blanco"}
];
```
![Image](https://github.com/user-attachments/assets/741004b5-1dd6-4efe-affe-46af1d2c7ee8)
<img width="1591" height="81" alt="image" src="https://github.com/user-attachments/assets/b33f802f-e0e8-489a-9f9e-8c36416a69f8" />

## while

Repite mientras la condición sea verdadera (puede ejecutarse 0 veces).

```javascript
// Factorial con while
const n = 5;
let r = 1, i = 2;
while (i <= n) {
  r *= i;
  i++;
}
console.log(r); // 120

```
Lo más clásico para poder ejecutar es usar un ciclo for 
```javascript
for (var i = 0; i < listaPersonas.length; i++) {
 console.log(listaPersonas[i].nombre);
 console.log(listaPersonas[i].apellidos);
}
```
![Image](https://github.com/user-attachments/assets/2079bcc2-8b86-4f96-9d76-18445392c1e6)
<img width="1617" height="81" alt="image" src="https://github.com/user-attachments/assets/03de78a7-3132-40e6-bd86-31196d4f4556" />
Como seria utilizando el ciclo for ...of
```javascript
for (var persona of listaPersonas) {
console.log(persona.nombre);
console.log(persona.apellidos);
}
```
![Image](https://github.com/user-attachments/assets/a1297200-aa42-493a-9f04-f323b61c48e1)
<img width="1607" height="81" alt="image" src="https://github.com/user-attachments/assets/6a85ef01-adad-49df-90c1-404ca7728d34" />

Como seria utilizando el ciclo for ... in 
```javascript
 for (var propiedad in listaPersonas) {
 // Imprime el valor de cada propiedad
 console.log(listaPersonas[propiedad]);
 }
```
![Image](https://github.com/user-attachments/assets/6b203890-fe4e-4fb4-b667-46456b18911a)
<img width="1612" height="81" alt="image" src="https://github.com/user-attachments/assets/c307e50f-ab23-429f-8f82-f1c6fff587ee" />

## do…while

Ejecuta el bloque al menos una vez, y luego verifica la condición.

```javascript
// Ejecuta al menos una vez
let conteo = 0;
do {
  console.log("Paso", conteo);
  conteo++;
} while (conteo < 3);
// Imprime Paso 0, Paso 1, Paso 2

```

## break y continue

•	break sale por completo del bucle.

•	continue salta a la siguiente iteración.

```javascript
// Suma solo impares hasta encontrar el 0
const datos = [5, 3, 8, 11, 0, 7];
let sumaImpares = 0;
for (const n of datos) {
  if (n === 0) break;       // corto el bucle
  if (n % 2 === 0) continue; // salto pares
  sumaImpares += n;
}
console.log(sumaImpares); // 5 + 3 + 11 = 19

```

Errores comunes: bucles infinitos (while(true) sin break), modificar el array mientras lo recorres, usar for...in en arrays (te da índices como strings y puede incluir propiedades añadidas).

# CAPÍTULO 6 - Funciones (declaración, expresiones, parámetros, retorno)

## Declaración de función

•	Tiene hoisting: puedes llamarla antes de su definición.

```javascript
console.log(suma(2, 3)); // 5
function suma(a, b) {
  return a + b;
}

```

## Expresión de función

•	Se asigna a una variable. No puedes usarla antes de la línea donde se define.

```javascript
const resta = function(a, b) {
  return a - b;
};
console.log(resta(7, 4)); // 3

```

## Arrow function (=>)

•	Sintaxis corta; no tiene su propio this ni arguments. No sirve como constructor.

```javascript
const mult = (a, b) => a * b;          // retorno implícito
const cuadrado = x => x * x;           // un parámetro → sin paréntesis
const toObj = (k, v) => ({ [k]: v });  // devolver objeto → usa paréntesis
console.log(mult(3, 4), cuadrado(5), toObj("id", 10));

```

## Parámetros

### Valores por defecto

```javascript
function saludar(nombre = "Invitado", idioma = "es") {
  return idioma === "es" ? `Hola, ${nombre}` : `Hello, ${nombre}`;
}
console.log(saludar());                // Hola, Invitado
console.log(saludar("Ana", "en"));     // Hello, Ana

```

## Parámetros rest (...)

### Agrupa argumentos adicionales en un array.

```javascript
function sumarTodos(...nums) {
  return nums.reduce((acc, n) => acc + n, 0);
}
console.log(sumarTodos(1, 2, 3, 4)); // 10

```

### Desestructuración en parámetros (con defaults)

Ideal para “parámetros nombrados” mediante objeto.

```javascript
function crearUsuario({ nombre, rol = "user", activo = true }) {
  return { nombre, rol, activo, creadoEn: new Date() };
}
console.log(crearUsuario({ nombre: "Ana", rol: "admin" }));

```

## Retorno (return)

•	Finaliza la función y devuelve un valor.

•	Puedes retornar objetos/arrays para “múltiples valores”.

```javascript
function dividir(a, b) {
  if (b === 0) return { ok: false, error: "División por cero" };
  return { ok: true, resultado: a / b };
}
console.log(dividir(10, 2)); // { ok: true, resultado: 5 }
console.log(dividir(5, 0));  // { ok: false, error: ... }

```
# CAPÍTULO 7 - Clipping y Masking con CSS

## Concepto

Dentro de las técnicas avanzadas de diseño web, el **Clipping** y el **Masking** en CSS representan recursos fundamentales para la manipulación visual de los elementos. Ambas técnicas tienen como finalidad alterar las áreas visibles de un elemento, aunque lo hacen mediante mecanismos distintos:

- **Clipping**: se basa en la utilización de la propiedad `clip-path`, la cual permite definir una región geométrica (círculos, elipses, polígonos, entre otros) que delimita la parte del elemento que será visible. El contenido fuera de la forma definida se oculta sin modificar realmente el DOM.  
- **Masking**: emplea una imagen o un gradiente como máscara mediante la propiedad `mask-image` (o `-webkit-mask-image` en algunos navegadores). La máscara determina qué partes del elemento serán visibles en función de la opacidad o transparencia de la imagen aplicada.  

Según Coyier (2021), estas herramientas amplían considerablemente la creatividad del diseñador, dado que permiten crear interfaces más dinámicas, con efectos visuales modernos sin necesidad de editar previamente las imágenes en un software externo.

## Ventajas

- **Mayor expresividad visual**: posibilitan el uso de formas y patrones personalizados que enriquecen el diseño de interfaces.  
- **Flexibilidad**: mientras el clipping se orienta a recortes geométricos, el masking admite imágenes complejas y gradientes.  
- **Optimización de recursos**: evita la necesidad de generar imágenes editadas previamente, ya que los efectos se logran directamente con código.  
- **Compatibilidad moderna**: ampliamente soportado en navegadores actuales, aunque en algunos casos se requiere prefijos específicos.  
- **Aplicaciones dinámicas**: se pueden integrar con transiciones y animaciones para efectos interactivos en páginas web.  

## Ejemplo de código

```css
/* CSS */
.clipped {
  width: 300px;
  height: 300px;
  background: url('https://picsum.photos/400') no-repeat center/cover;
  clip-path: circle(50% at 50% 50%);
}

.masked {
  width: 300px;
  height: 300px;
  background: url('https://picsum.photos/400') no-repeat center/cover;
  -webkit-mask-image: linear-gradient(to bottom, black 70%, transparent 100%);
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-size: cover;
}
```

```html
<!-- HTML -->
<div class="clipped"></div>
<br>
<div class="masked"></div>
```

## Resultado

El primer ejemplo aplica un recorte circular a la imagen de fondo del elemento, mostrándola como si estuviera contenida en un círculo perfecto. El segundo ejemplo utiliza un degradado como máscara, de modo que la parte inferior de la imagen se desvanece progresivamente hasta volverse transparente.

# CAPITULO 8 - Propiedades y Contenedores CSS (Container Queries)
Los CSS Container Queries son el mismo concepto de las Media Queries, pero en lugar de estar orientados a modificar los estilos dependiendo del tamaño de la página o dispositivo (viewport), lo hace dependiendo de un contenedor padre (o ancestro). De esta forma, podemos cambiar el tamaño de ciertos elementos y hacer que tengan una forma o unos estilos dependiendo del contexto donde se encuentren.

------------

### ELEMENTO CONTENEDOR
Para empezar tenemos que determinar cuál será el elemento contenedor al que vamos a hacer referencia. En dicho elemento, necesitaremos establecer las siguientes propiedades:

#### PROPIEDADES

**Propiedad container-name:** La propiedad container-name le da un nombre de contenedor al elemento en el que nos encontramos. Sin este nombre no podremos hacer referencia luego, en la regla @container.

**ejemplo:**

```css
.container {
  container-name: titulo;
}
```

**Propiedad container-type:** La propiedad container-type, establece el tipo de tamaño que va a tener el contenedor en cuestión, donde puede ser:
 - size: Elementos de tipo bloque (alto y ancho).
 -  inline-size: Elementos de tipo linea (solo ancho).
 
**ejemplo**
```css
 .container {
  container-name: titulo;
  container-type: inline-size;
}
```
**Propiedad container:** En esta propiedad podemos indicar **dos valores**, el valor de la propiedad **container-name** y el valor de la propiedad **container-type**, pero siempre separadas por un **/**.

**ejemplo**

```css
 .container {
  container: titulo / inline-size;
}
```
------------
### REGLA CONTAINER
Una vez tenemos nuestro contenedor definido, debemos establecer una regla @container que es muy parecido a las reglas @media, pero en este caso establece una condición para aplicar estilos a un contenedor en concreto.

**SINTAXIS**
```css
@container <nombre del contenedor> (<condición>)
```
**Ejemplo**
```css
.container {
  border: 1px solid red;
  color: black;
  container: titulo;
}

@container logo (width <= 550px) {
  .h1 {
    color: blue;
  }
}
```

------------

### UNIDADES DE CONTENEDORES
Cuando nos encontramos en el interior de una regla @container podemos utilizar ciertas unidades especiales como cqw, cqh, cqi, cqb, cqmin o cqmax.
Los componentes que usan unidades de longitud relativas a su contenedor son más flexibles para su uso en diferentes contenedores sin tener que recalcular valores de longitud concretos.

**Las unidades de longitud de la consulta del contenedor son:**
- cqw: 1% del ancho de un contenedor de consulta
- cqh: 1% de la altura de un contenedor de consulta
- cqi: 1% del tamaño en línea de un contenedor de consulta
- cqb: 1% del tamaño del bloque de un contenedor de consulta
- cqmin: El valor más pequeño de uno cqi o cqb
- cqmax: El valor mayor de uno cqi u otro cqb

```css
@container (width > 700px) {
  .card h2 {
    font-size: max(1.5em, 1.23em + 2cqi);
  }
}
```
# CAPITULO 9 - Filtros y Efectos Visuales avanzados

Los filtros en CSS permiten añadir efectos visuales, como sepia, ajustes de brillo, contraste u otros, directamente desde el navegador y de manera instantánea, sin modificar de forma permanente la imagen original.

Se pueden aplicar desde dos propiedades CSS diferentes:

Propiedad  | Descripción
------------- | -------------
Filter  | Aplica un filtro concreto a un elemento HTML y todos los de su interior.
backdrop-filter  | 	Aplica un filtro concreto al fondo de un elemento HTML, sin que afecte a su interior.

### PROPIEDAD FILTER
filter acepta funciones de filtrado (por ejemplo, blur(), brightness(), contrast(), grayscale(), sepia()) que modifican la representación visual del elemento en el renderizado final de la página.
```css
img {
  filter: grayscale(100%);
  transition: filter 1s;
  width: 200px;
}

img:hover {
  filter: grayscale(0%);
}
```
#### FUNCIONES DE FILTROS
Función  | Significado | Valor
------------- | ------------- | -------------
grayscale  | Escala de blanco y negro | percent - number
blur | 	Desenfoque Gausiano | size
sepia | Grado de color sepia | percent - number
saturate | Grado de saturación | percent - number
opacity | Grado de transparencia | percent - number
brightness | Brillo | percent - number
contrast | Contraste | percent - number
hue-rotate | Rotación de color (matiz) | angle
invert | Invertir | percent - number
drop-shadow | Sombra idéntica | posx posy size color

**PORCENTAJES O NÚMEROS**
- PERCENT: Valor porcentual (0%, 50%,100%,....)
- NUMBER: Valor númerico (0, 0.5, 1,.....)

**ejemplo grayscale**
```css
#img1 {
    filter: grayscale(100%);
}
```
**ejemplo blur**
```css
#img2 {
    filter: blur(5px);
}
```
**ejemplo sepia**
```css
#img3 {
    filter: sepia(100%);
}
```
**ejemplo saturate**
```css
#img4 {
    filter: saturate(200%);
}
```
**ejemplo opacity**
```css
#img5 {
    filter: opacity(50%);
}
```
**ejemplo brigthness **
```css
#img6 {
    filter: brightness(230%);
}
```
**ejemplo contrast**
```css
#img7 {
    filter: contrast(250%);
}
```
**ejemplo invert**
```css
#img8 {
    filter: invert(80%);
}
```
**ejemplo hue-rotate**
```css
#img9 {
    filter: hue-rotate(230deg);
}
```
**ejemplo drop-shadow**
```css
#img10 {
    filter: drop-shadow(5px 5px 10px black);
}
```

### PROPIEDAD BACKDROP-FILTER
La propiedad backdrop-filter en CSS sirve para aplicar efectos visuales (como desenfoque, brillo, contraste, etc.) al fondo que hay detrás de un elemento, sin alterar el contenido interno de ese mismo elemento.

Es decir, mientras que filter afecta directamente al elemento y a todo lo que contiene, backdrop-filter solo modifica la parte del fondo que se ve a través del elemento.

**ejemplo**
```css
#img11 {
    backdrop-filter: blur(10px);
}
```

# CAPITULO 10 - Técnicas de Performance y Optimización en CSS

## Concepto
Según Vázquez Sanisidro (2017), el **CSS es un recurso crítico de bloqueo de renderizado**, es decir, mientras el navegador no procese las hojas de estilo, la página no puede mostrarse al usuario. Por ello, la optimización de CSS busca **reducir el tiempo de renderizado inicial** aplicando técnicas como:

- Uso de **CSS crítico (Critical CSS)** para cargar primero los estilos mínimos necesarios en la parte visible.  
- **Minificación** de archivos para reducir su tamaño eliminando espacios y comentarios.  
- **Carga diferida o asíncrona** del CSS no crítico para evitar bloquear la renderización.  
- Evitar el uso de **estilos inline**, ya que son más lentos de procesar y no se pueden cachear.  
- Optimización de **fuentes web** con `@font-face` y la propiedad `font-display` para evitar pantallas en blanco mientras se descargan.  

En palabras del autor:  
> “Lo ideal es identificar los estilos críticos para el diseño de la parte superior de la página y cargarlos junto al html (…) y retrasar la carga del resto de los recursos CSS después del html necesario para mostrar la parte superior de la página” [1].

## Ventajas
- Mejora perceptible en el tiempo de carga inicial de la página.  
- Evita que el usuario vea una página en blanco mientras se cargan los estilos.  
- Reduce el tamaño de los archivos CSS y acelera su descarga.  
- Permite aprovechar nuevas capacidades de los navegadores modernos (como `preload` y `font-display`).  
- Incrementa la retención de usuarios y el posicionamiento en buscadores (SEO).  

## Ejemplo de Código
| Código No optimizado |
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo sin optimización</title>

  <!-- ❌ Múltiples hojas de estilo que bloquean el renderizado -->
  <link rel="stylesheet" href="reset.css">
  <link rel="stylesheet" href="layout.css">
  <link rel="stylesheet" href="theme.css">
  <link rel="stylesheet" href="fonts.css">

  <!-- ❌ Fuente sin font-display (puede mostrar pantalla en blanco mientras carga) -->
  <style>
    @font-face {
      font-family: 'MiFuente';
      src: url('mifuente.woff2') format('woff2');
    }
  </style>

  <!-- ❌ Estilos inline dispersos -->
</head>
<body style="margin:0; padding:0; background:#f4f4f4;">
  <h1 style="color:#333; text-align:center; margin-top:50px;">
    Bienvenido a mi sitio sin optimización
  </h1>
  <p style="font-size:18px; color:#555; text-align:center;">
    Este texto tarda más en cargarse debido a malas prácticas en el uso de CSS.
  </p>
</body>
</html>
```
| Código Optimizado |
```html
<style>
  /* ✅ CSS crítico inline (se carga primero) */
  body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f4f4f4; }
  h1 { font-size: 2em; color: darkblue; text-align: center; margin-top: 50px; }
</style>

<!-- ✅ Carga diferida de CSS no crítico -->
<link rel="preload" href="styles.min.css" as="style" onload="this.onload=null;this.rel='stylesheet'">
<noscript><link rel="stylesheet" href="styles.min.css"></noscript>

<!-- ✅ Fuente optimizada con font-display -->
<style>
  @font-face {
    font-family: 'MiFuente';
    src: url('mifuente.woff2') format('woff2'),
         url('mifuente.woff') format('woff');
    font-display: swap; /* Muestra texto con fuente del sistema mientras carga */
  }
</style>
```

# CONCLUSIÓN

El estudio realizado permite establecer que la optimización de CSS constituye un componente fundamental en el proceso de mejora del rendimiento de los sitios web. Tal como sostiene Vázquez Sanisidro (2017), el uso inadecuado de las hojas de estilo puede generar un bloqueo en el renderizado de la página, retrasando la visualización de los contenidos y afectando de manera directa la experiencia del usuario. En este sentido, la investigación demuestra que la optimización de CSS no debe entenderse únicamente como una cuestión estética, sino como una práctica estratégica que influye en la eficiencia técnica y en la percepción global de calidad de un sitio web.

Entre las técnicas analizadas, destacan la aplicación de CSS crítico, que permite mostrar de inmediato los elementos esenciales de la página; la carga diferida de estilos no prioritarios, que evita bloqueos en el renderizado inicial; y la minificación de archivos, que reduce el peso de los recursos y acelera su descarga. De igual forma, la exclusión de estilos inline favorece tanto la eficiencia del renderizado como la mantenibilidad del código, y la optimización de fuentes web mediante la propiedad font-display contribuye a garantizar que el contenido textual sea accesible desde el primer momento, incluso en conexiones limitadas.

Los beneficios derivados de estas prácticas abarcan distintas dimensiones: desde la mejora en los tiempos de carga y la reducción de la tasa de abandono, hasta un mayor posicionamiento en motores de búsqueda y una mejor accesibilidad en entornos de baja capacidad. Además, al promover un código más estructurado y modular, la optimización facilita la escalabilidad y el mantenimiento de proyectos a largo plazo, consolidándose como un estándar de calidad en el desarrollo web moderno.

En conclusión, la optimización de CSS no representa una acción opcional, sino un requisito indispensable para el diseño de aplicaciones y sitios web eficientes, accesibles y competitivos. La incorporación de estas prácticas desde las etapas iniciales del desarrollo asegura no solo un mejor desempeño técnico, sino también una experiencia de usuario más satisfactoria, lo cual constituye un factor decisivo en el actual entorno digital caracterizado por la inmediatez y la alta exigencia de los usuarios.

# REFERENCIA BIBLIOGRÁFICA

- Manz. (s. f.). ¿Qué es CSS? En LenguajeCSS.com. https://lenguajecss.com/css/introduccion/que-es-css/
- ManzDev. (2017, 5 de abril). Variables CSS: CSS Custom Properties. https://lenguajecss.com/css/variables-css/css-custom-properties/
- World Wide Web Consortium (s. f.). About us. W3C. https://www.w3.org/about/
- A. Vázquez Sanisidro, Optimización de Páginas Web: Visión teórica y análisis práctico, Tesis de Grado, Dpto. de Ingeniería Telemática, Univ. de Sevilla, Sevilla,     España, 2017.
- Coyier, C. (2021). *Clipping and Masking in CSS*. CSS-Tricks. Recuperado de https://css-tricks.com/clipping-masking-css/  
- Meyer, E. A. (2018). *CSS: The Definitive Guide* (4.ª ed.). O’Reilly Media.  
- Mozilla Developer Network (MDN). (2022). *clip-path*. Mozilla Foundation. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/clip-path  
- Mozilla Developer Network (MDN). (2022). *mask-image*. Mozilla Foundation. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/mask-image
- Keith, J. (2020). *A complete guide to CSS Scroll Snap*. CSS-Tricks. Recuperado de https://css-tricks.com/practical-guide-to-scroll-snap/  
- Mozilla Developer Network (MDN). (2022). *CSS Scroll Snap*. Mozilla Foundation. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/CSS_Scroll_Snap  
- W3C. (2019). *CSS Scroll Snap Module Level 1*. World Wide Web Consortium. Recuperado de https://www.w3.org/TR/css-scroll-snap-1/
- Manz. (s. f.).  Filtros CSS En LenguajeCSS.com.https://lenguajecss.com/css/efectos/filtros-css/
- Manz. (s. f.). CSS Container Queries En LenguajeCSS.com.https://lenguajecss.com/css/responsive-web-design/css-container-queries/
