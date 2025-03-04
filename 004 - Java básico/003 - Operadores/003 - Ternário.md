Operador ternário é uma maneira simplificada de realizar condições, podendo escolher entre dois valores.

Pense no ternário como se fosse uma condição `if`, porém toda a sua estrutura estará em apenas uma linha.

O operador ternário é representado pelo símbolo `?:`, aplicando na estrutura da seguinte forma:
```java
<Expressão Condicional> ? <Caso a condição seja verdadeira> : <Caso a condição seja falsa>
```

Exemplo:

```java
int a,b;  
  
a = 5;  
b = 5;  
  
String resultado = a==b ? "verdadeiro" : "falso";
```