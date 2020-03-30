## Condicionales

Nos ayudan a saber que decisión tomar (así como tu ❤️).

## `if`

## Sintaxis.
```js
  if (condición) {
    // Tu hermoso código que se ejecutará en caso de ser positivo. 🤩
  }
```

En donde:

 * `if`: es una _palabra reservada_ y siempre debe de ir en minúscula.
 * _condición_ : es la expresión a evaluar, esta debe de ser *true* (valor booleano).
 * `{}` : dentro de las llaves estará el código que quieres ejecutar, solo si la condición
 fue verdadera. 

## Ejemplos 👩🏽‍💻😉
https://repl.it/@zz_nn/if

## `if...else`
Aqui nuestro `if` ya no esta solito, ahora esta la palabra reservada `else` que nos ayuda a manejar el caso en donde nuestra condición no sea verdadera.

## Sintaxis.
```js
  if (condición) {
    // Tu hermoso código que se ejecutará en caso de ser positivo. 🤩
  }else {
    // Tu hermoso código que será ejecutado en caso de que la condición sea falsa. 😕
  }
```

como puedes observar el `else` no tiene parentesis, pues no tiene nada que evaluar.

## Ejemplos 👩🏽‍💻😉
https://repl.it/@zz_nn/if-else

## `else if()`
Aquí nuestra sintaxis cambia 😱, para entenderla puedes traducirla como: _entonces si_. 
Es como si nos dieran otra opción a evaluar.

## Sintaxis.
```js
  if (condición) {
    // Tu hermoso código que se ejecutará en caso de ser positivo. 🤩
  } else if (condición) {
    // Tu hermoso código que se ejecutará en caso de ser positivo. 🤩
  } else {
    // Tu hermoso código que será ejecutado en caso de que la condición sea falsa. 😕
  }
```

para usar `else if()`, necesitas si o si el `if()` antes, así como se muestra en la sintaxis 👆

## Ejemplos 👩🏽‍💻😉
https://repl.it/@zz_nn/elseIF

## Anidando `if ... else`
Anidación! 🤯, eso significa que puedes añadir un `if...else` dentro de otra 
declaración `if...else`.

## Sintaxis.
```js
  if (condición) {
    // código que se ejecutará en caso de ser positivo.
    if(condición2) {
      // código que se ejecutará en caso de ser positivo el primer if y el segundo.
    }else {
      // código que será ejecutado en caso de que la condición sea falsa, pero
      // considera que este else es opcional.
    }
  } else if (condición) {
    // código que se ejecutará en caso de ser positivo.
  } else {
    // código que será ejecutado en caso de que la condición sea falsa.
  }
```
Puedes agregar los `if..else` que necesites.

## Ejemplos 👩🏽‍💻😉
https://repl.it/@zz_nn/anidando-ifElse

## operador condicional (ternario)
Este operador se usa como atajo para el condicional `if..else`.

## Sintaxis.
```js
condición ? acción1 : acción2 
```
En donde:

+ condición: es la expresión a evaluar, que puede ser true ó false.
* acción1, acción2: son las acciones que se deben hacer según la condición.

Si la condición es true, el operador retorna el valor de la acción1; de lo contrario, devuelve el valor de la acción2.

## Ejemplos 👩🏽‍💻😉
https://repl.it/@zz_nn/ternario

## Switch (Condicional de selección)
Se usa para realizar diferentes acciones basadas en diferentes condiciones.

## Sintaxis.
```js
switch(expresión) {
  case valor1:
    // código que se ejecuta si la expresión coincide con el valor1
    break;
  case valor2:
    // código que se ejecuta si la expresión coincide con el valor2
    break;
  default:
    // código que se ejecuta cuando ninguno de los valores coinciden con el valor de la expresión
}
```
En donde:

+ expresión: es comparada con el valor de cada `case`
* `case valorN`: son comparadas con la expresión, si coinciden se ejecutará el código que haya 
en el `case` y terminará hasta el final del `switch` o donde encuentre la palabra reservada `break;`,
por cierto `break` no es obligatorio pero ten en cuenta que si no lo pones puede ejecutar código que 
no cumpla con la expresión ya que no sabrá donde debe terminar, así que te recomiendo ponerlo para evitar dolores de cabeza.😉
* `default`: es ejecutada cuando el valor de la expresión **NO** coindice con algún valor declarado en `case`.

## Ejemplos 👩🏽‍💻😉
https://repl.it/@zz_nn/switch

### Referencias:
* [if...else](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/if...else)
* [Estructura IF](https://desarrolloweb.com/articulos/544.php)
* [Operador condicional(ternario)](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Conditional_Operator)
* [switch](https://www.w3schools.com/js/js_switch.asp)