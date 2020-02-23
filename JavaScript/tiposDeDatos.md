## Definición.
JavaScript es un lenguaje de tipado débil o dinámico. Esto significa que no es necesario declarar el tipo de variable antes de usarla.

A diferencia de otros lenguajes como C#, en donde especificamos el tipo de valor al declarar
cada variable.

```
int edad = 38;
string nombre = "Marcel";
bool b = false;
```
## String
Un string es una cadena de caracteres, es el tipo de dato que se utiliza para representar un texto.
En donde cada carácter se le asigna una posición, empezando por el primer carácter en la posición 0, el segundo en la posición 1 y así sucesivamente.
Para declarar un string debemos poner el contenido entre comillas.
# Ejemplo:
"soy un string";
## Numbers
Son valores numéricos, incluyendo números positivos, negativos, enteros y decimales.

Además, el tipo de datos number tiene tres valores simbólicos: +Infinity, -Infinity y NaN (no-un-número).
# Ejemplo:
`let numero = 20;`

`let numeroConDecimal = 20.5`
### ¿Qué podemos hacer con el tipo numérico? 🤔
Podemos hacer operaciones aritméticas, como: suma, resta, división, multiplicación, etc.

* [Ejemplos.](https://repl.it/@nnzz/tipos-de-datos-numericos) 😉

## Boolean.

Puede tener dos valores: 'true' ó 'false'.

### ¿Qué podemos hacer con los booleans? 🤔
Podemos hacer comparaciones entre valores usando los signos `>` y `<` (mayor que y menor que), `===` y `!==` ,(igual que o diferente que)  ó `>=` y `<=` (mayor igual que y menor igual que), cuando aplicamos dichas comparaciones los resultados que obtendremos serán boolean.

* [Ejemplos.](https://repl.it/@nnzz/Booleans) 😉

## Undefined y Null
Ambas nos indican que no se les asigno un valor significativo (number, string, etc), por lo cual su información no es valida.
Null: tiene el valor null.
Undefined: es una variable a la cual no se le asigno ningún valor.

## Object
En JavaScript los objetos son una collección de propiedades.

### ejemplo:

```
let persona = {
  nombre: "Nancy",
  edad: 25,
  ciudad: "México"
};
```

### Referencias:
* [Tipos de datos en javascript](https://www.netinetidesign.com/post/tipos-de-datos-en-javascript/)
* [Tipos de datos y estructuras en JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript/Data_structures)
