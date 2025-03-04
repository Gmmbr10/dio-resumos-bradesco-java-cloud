
São operadores que são aplicados junto a outro operador aritmético. Eles fazem trabalhos como incrementar, decrementar, inverter valores numéricos ou booleanos.

- **(+) Operador unário de valor positivo** - indica valores positivos, mesmo sem aparecer explicitamente;
- **(-) Operador unário de valor negativo** - nega um número ou expressão aritmética;
- **(++) Operador unário de incremento de valor** - incrementa o valor em 1 unidade;
- **(--) Operador unário de decremento de valor** - decrementa o valor em 1 unidade;
- **(!) Operador unário lógico de negação** - nega o valor de uma expressão booleana;

```java

int numero = 5;  
  
int numeroNegativo = - numero;  
// deixando o valor negativo  
  
int numeroPositivo = numeroNegativo * - 1;  
// deixando o valor positivo  
  
numero++;  
// adicionando 1 ao valor da variável  
  
numero--;  
// tirando 1 ao valor da variável

boolean trabalhando = true;  
  
trabalhando = !trabalhando;  
// inverte o valor booleano, o true vira false e o false vira true

```

> **Atenção**
> 
> Quando você coloca (++) ou (--) deve-se ter cautela.
> 
> `System.out.println(numero++)` vai exibir primeiro o valor da variável, e depois incrementar
> 
> `System.out.println(++numero)` vai primeiro incrementar e depois exibir
> 
> Quando for usar, tenha cautela para incrementar ou decrementar