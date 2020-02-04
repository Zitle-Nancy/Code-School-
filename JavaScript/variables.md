# Variables

## Definición.
Las variables nos ayudan a almacenar un valor variante (que puede cambiar).
## Nombrando Variables
Al momento de nombrar nuestras variables debemos considerar algunas reglas:
  - No incluir espacios
      * `mi variable= '1';` :-1:
      * `miVariable = '1:` :+1:
  - No debe ser una [palabra reservada](https://github.com/Zitle-Nancy/Code-School-/blob/version-1/JavaScript/variables.md#espera-qu%C3%A9-es-una-palabra-reservada-scream)
      * `var = '1';` :-1:
      * `variable = '1:` :+1:
  - No comenzar con números, pero si pueden contener números, ejemplo:
      * `1variable = '1';` :-1:
      * `variable1 = '1:` :+1:
  - No contener signos de puntuación, sin embargo acepta signos como: $ y _
    Ejemplos:
      * `variable? = '1';` :-1:
      * `variable$ = '1:` :+1:
      * `$variable = '1:` :+1:

### Sugerencias para nombrar variables
  - camel case: ya que no podemos incluir espacios al nombrar una variables, podemos usar la convención de camel case. La convención nos indica que el nombre de la variable empieza con una letra minúscula y se coloca en mayúscula la primera letra de las palabras que continúan.
  
  Ejemplo: 
  `userName`
  `userList`

  Se llama camel case porque simula una joroba de camello.[mas información](https://es.wikipedia.org/wiki/Camel_case)
  - Utilizar nombres en inglés.
  - Utiliza nombres descriptivos. Considera que otras programadoras leeran tu código por lo tanto asegurate de ser descritiva al nombrarlas.

## Sintaxis.
- `var variable1 = value;`
- `let variable2 = value;`

Donde

  * _variable1, variable2_ es el nombre de la variable que has declarado.
  * _value_ es el valor que tendra.
  * _=_ con el simbolo de igual haces la asignación entre el nombre y el valor.
## Ejemplos:
Vamos a crear variables para guardar nuestra información:
  - `var nombre = 'nancy';`
  - `let apellido = 'zitle';`

## var, let y const, (sus diferencias).

Cuando Javascript fue creado, sólo existía `var` para definir una variable, sin embargo `var` tiene algunos problemas en cuanto a su función, es por eso que se creó `let` y `const` en versiones modernas de JS (ECMAScript 6).

- [Ejemplo de los errores que produce var :smirk:](https://repl.it/@nnzz/Usando-var)
- [Ejemplo de como let nos ayuda :blush: ](https://repl.it/@nnzz/Usando-let)

**Las diferencias**

Como pudiste ver en los ejemplos la principal diferencia entre `let` y `var` es el _scope_ que tienen. El _scope_ es el alcance dentro de nuestro programa.

¿Y const?

La palabra reservada _const_ se utiliza para declarar **constantes**, es decir valores que no se pueden reasignar porque su valor no va a cambiar, por ejemplo _PI_, siempre será 3.1416
[Ejemplo de const ](https://repl.it/@nnzz/usando-const)

## Espera, ¿Qué es una palabra reservada? :scream:
Las palabras reservadas son aquellas que forman parte de la sintaxis del lenguaje de programación, en 
este caso de JavaScript, estas palabras reservadas no debemos usarlas al nombrar variables o funciones,así evitaremos problemas en nuestro código.
Algunas de ellas son las siguientes (no te preocupes si no las conoces, poco a poco las iremos aprendiendo :wink:):

```await break case catch class const continue debugger default delete do else export extends finally for function if import in instanceof new return super switch this throw try typeof var while ```

### Referencias:
* [what is JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/Qu%C3%A9_es_JavaScript)
* [Variables](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/Variables)
* [Palabras reservadas](https://tutobasico.com/reservadas-javascript/)
* [Palabras reservadas](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Palabras_Reservadas)
* [Diferencias entre let y var](https://www.analyticslane.com/2019/06/10/diferencias-entre-var-y-let-en-javascript/)