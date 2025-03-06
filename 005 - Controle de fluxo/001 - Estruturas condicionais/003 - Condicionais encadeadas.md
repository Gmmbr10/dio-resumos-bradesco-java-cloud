Em um controle de fluxo, nem sempre nos limitamos ao **se** (`if`) e **senão** (`else`), podemos ter uma terceira, quarta ou inúmeras condições.

Exemplo:

```java
int nota = 6;  
  
if ( nota >= 7 ) {  
    // verdadeiro  
    System.out.println("Aprovado");  
} else if (nota >= 5) {  
    // apenas a segunda afirmação é verdadeira  
    System.out.println("Recuperação");  
} else {  
    // falso  
    System.out.println("Reprovado");  
}
```