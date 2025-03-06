Como vimos em operadores, podemos abreviar nosso algoritmo condicional refatorando o código com o conceito de operador ternário.

Exemplo:

```java
int nota = 6;  

// String resultado = nota >= 7 ? "Aprovado" : "Reprovado";  
String resultado = nota >= 7 ? "Aprovado" : nota >= 5 ? "Recuperação" : "Reprovado" ;  

System.out.println(resultado);
```