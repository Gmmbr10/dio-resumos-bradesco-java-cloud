Símbolos especiais que tem um significado próprio para a linguagem, são associados a operações específicas.

## Classificando os operadores

### Atribuição
Representado pelo símbolo `=` (igual)

É utilizado para definir o valor inicial ou sobrescrever o valor de uma variável.

### Aritméticos
Usado para realizar operações matemáticas entre valores numéricos, podendo se tornar uma expressão complexa.

| Símbolo | Significado   |
| ------- | ------------- |
| +       | Adição        |
| -       | Subtração     |
| /       | Divisão       |
| *       | Multiplicação |
| %       | Módulo        |

> **Atenção**
> 
> Módulo serve para encontrar o resto de uma divisão
>
> O operador de adição, em textos, servirá para concatenar textos.

## Exemplo no código

```java
int soma = 1 + 1;  
  
int subtracao = 2 - 1;  
  
int divisao = 4 / 2;  
  
int multiplicacao = 2 * 2;  
  
int modulo = 9 % 2;  
  
// concatenando Strings
String concatenacao = "concatenação";  
  
concatenacao = 1+1+1+"1";
// soma enquanto não encontrar a string  
  
concatenacao = 1+"1"+1+1;
// depois de encontrar uma string ele concatena  
  
concatenacao = "1"+(1+1+1);
// quando se tem a expressão, primeiro realiza ela, para depois realizar a concatenação  
```
