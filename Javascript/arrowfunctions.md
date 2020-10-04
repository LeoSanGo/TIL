# Arrow Functions

Tem como objetivo diminuir a complexidade e verbosidade das funções usadas em javascript

Em funções como:
```js
hello = function() {
  return "Hello World";
}
```

Podem ser escritas como:
```js
hello = () => {
  return "Hello World";
}
```

Ou de forma mai simplista:
```js
hello = () => "Hello World";

```
Esta expressão acima é aceitavel desde que contenha apenas uma declaraçao.


Parênteses são opcionais quando só há um nome de parâmetro:
```js
(singleParam) => { statements }
singleParam => { statements }
```
