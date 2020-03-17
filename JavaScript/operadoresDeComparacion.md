## Definición.

Nos ayudan a comparar valores y la respuesta es un boolean (true o false).

### Operadores de igualdad
## Igualdad

Convierte los operandos si no son del mismo tipo, luego aplica una comparación estricta en su contenido.

Sintaxis.

`x == y`
##  Ejemplos

```  
1    ==  1         // true
'1'  ==  1         // true
1    == '1'        // true
0    == false      // true
10   == 20         // false
```

## Desigualdad
Devuelve verdadero si los operandos no son iguales.
Si los operandos no son del mismo tipo, JavaScript intenta convertir los operandos a un tipo apropiado para la comparación.

Sintaxis

`x != y`

## Ejemplos

```
1 !=   2     // true
1 !=  '1'    // false
1 !=  "1"    // false
1 !=  true   // false
0 !=  false  // false
```

## Identidad / igualdad estricta (===)
Devuelve verdadero si los operandos son estrictamente iguales (valor y tipo de dato).

Sintaxis

`x === y`

## Ejemplos 

```
  3 === 3   // true
  3 === '3' // false
```

## Sin identidad / desigualdad estricta (!==)
El operador sin identidad devuelve verdadero si los operandos no son iguales o del mismo tipo.

Sintaxis

`x === y`

## Ejemplos 

```
  3 === 3   // true
  3 === '3' // false
```

## Operadores relacionales
## Operador mayor que (>)
Devuelve verdadero si el operando izquierdo es **mayor** que el operando derecho.

Sintaxis

`x > y`
## Ejemplos

``` 4 > 3 // true ```
## Operador mayor o igual (>=)
Devuelve verdadero si el operando izquierdo es **mayor o igual** que el operando derecho.

Sintaxis

`x >= y`
## Ejemplos

``` 
  4 >= 3 // true
  3 >= 3 // true
```

## Operador menor que (<)
Devuelve verdadero si el operando de la izquierda es **menor** que el operando de la derecha.

Sintaxis

`x < y`

## Ejemplos

```3 < 4 // true```

## Operador menor o igual (<=)
Devuelve verdadero si el operando izquierdo es **menor o igual** que el operando derecho.

Sintaxis

`x <= y`

## Ejemplos

```
3 <= 4 // true
```

### Referencias:
* [Operadores](https://uniwebsidad.com/libros/javascript/capitulo-3/operadores)
* [Operadores de Comparación](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Comparison_Operators)