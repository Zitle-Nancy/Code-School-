## Definición.

JavaScript soporta tres operadores lógicos: _and_, _or_ y _not_.

* El operador `&&` representa el operador lógico and ("y"), su resultado es verdadero **sólo si los dos valores dados son verdaderos**. 

* El operador `||` denota la operación lógica or ("o"), devuelve verdadero **si cualquiera de los dos valores dados es verdadero**. 

* Not (Negación) es escrito con un símbolo de admiración !. Es un operador binario que invierte el valor original, ejemplo: !true produce false y !false produce true.

```
true && true
// retorna: true

true && false
// retorna: false

false && false
// retorna: false

true || true
// retorna: true

true || false
// retorna: true

!true
// retorna: false

!false
// retorna: true
```

### Referencias:
* [Expresiones y operadores](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Expressions_and_Operators)