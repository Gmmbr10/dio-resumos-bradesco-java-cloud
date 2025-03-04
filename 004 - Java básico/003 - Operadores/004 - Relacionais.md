Os operadores relacionais verificam a relação entre duas variáveis ou expressões. Definindo se o operando à esquerda é igual, diferente, menor, menor igual, maior ou maior igual ao operando à direita, retornando um valor booleano como resultado.

| Operador | Significado    |
| -------- | -------------- |
| `==`     | Igual a        |
| `!=`     | Diferente      |
| `>`      | Maior que      |
| `>=`     | Maior ou igual |
| `<`      | Menor que      |
| `<=`     | Menor ou igual |
Exemplo:

```java
int numero1 = 4;  
int numero2 = 10;  
  
boolean verdadeiroFalso = numero1 == numero2;  
  
System.out.println("número 1 é igual ao número 2? " + verdadeiroFalso);  
  
verdadeiroFalso = numero1 != numero2;  
  
System.out.println("número 1 é diferente do número 2? " + verdadeiroFalso);  
  
verdadeiroFalso = numero1 > numero2;  
  
System.out.println("número 1 é maior que o número 2? " + verdadeiroFalso);  
  
verdadeiroFalso = numero1 >= numero2;  
  
System.out.println("número 1 é maior ou igual ao número 2? " + verdadeiroFalso);  
verdadeiroFalso = numero1 < numero2;  
  
System.out.println("número 1 é menor que o número 2? " + verdadeiroFalso);  
  
verdadeiroFalso = numero1 <= numero2;  
  
System.out.println("número 1 é menor ou igual ao número 2? " + verdadeiroFalso);
```

> **Atenção**
> 
> Os operadores servem para comparar os valores das variáveis.
> 
> Quando se trata de comparar classes, dependendo da forma como foi instanciado, o valor pode dar `false`
> Por esse motivo, quando você for comparar textos, use o método `.equals(valor a ser comparado)`