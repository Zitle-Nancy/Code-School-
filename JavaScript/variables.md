# Variables

## Definición.
Las variables nos ayudan a almacenar un valor variante (que puede cambiar).
## Nombrando Variables
Al momento de nombrar nuestras variables debemos considerar algunas reglas:
  - No debe incluir espacios
      * `mi variable= '1';` :-1:
      * `miVariable = '1:` :+1:
  - No debe ser una [palabra reservada]().
      * `var = '1';` :-1:
      * `variable = '1:` :+1:
  - No debe comenzar con números, pero si pueden contener números, ejemplo:
      * `1variable = '1';` :-1:
      * `variable1 = '1:` :+1:
  - No debe contener signos de puntuación, sin embargo acepta signos $ y _
    Ejemplos:
      * `variable? = '1';` :-1:
      * `variable$ = '1:` :+1:
      * `$variable = '1:` :+1:
## Sintaxis.
`var variable1 = value;`
`let variable2 = value;`
---
Donde:
  - _variable1, variable2_ es el nombre de la variable que has declarado.
  - _value_ es el valor que tendra.
  - _=_ con el simbolo de igual haces la asignación entre el nombre y el valor.
## Ejemplos:
Vamos a crear variables para guardar nuestra información:
  - `var nombre = 'nancy';`
  - `let apellido = 'zitle';`
## var, let y const, (sus diferencias).
Cuando Javascript fue creado, sólo existía `var` para definir una variable, sin embargo `var` tiene algunos problemas en cuanto a su función, es por eso que se creó `let` y `const` en versiones modernas de JS (ECMAScript 6).
---
[Ejemplo de los errores que produce var :smirk:](https://repl.it/@nnzz/Usando-var)
---
[Ejemplo de como let nos ayuda :blush: ](https://repl.it/@nnzz/Usando-let)
**Las diferencias**
Como pudiste ver en los ejemplos la principal diferencia entre `let` y `var` es el _scope_ que tienen. El _scope_ es el alcance dentro de nuestro programa.
---
¿Y const?
La palabra reservada _const_ se utiliza para declarar **constantes**, es decir valores que no se pueden reasignar porque su valor no va a cambiar, por ejemplo _PI_, siempre será 3.1416
[Ejemplo de const ](https://repl.it/@nnzz/usando-const)
---
Espera, ¿Qué es una palabra reservada? :scream:
Las palabras reservadas son aquellas que forman parte de la sintaxis del lenguaje de programación, en 
este caso de JavaScript, estas palabras reservadas no debemos usarlas al nombrar variables o funciones,así evitaremos problemas en nuestro código.
Algunas de ellas son las siguientes (no te preocupes si no las conoces, poco a poco las iremos aprendiendo :wink:):
---
```await break case catch class const continue debugger default delete do else export extends finally for function if import in instanceof new return super switch this throw try typeof var while ```
