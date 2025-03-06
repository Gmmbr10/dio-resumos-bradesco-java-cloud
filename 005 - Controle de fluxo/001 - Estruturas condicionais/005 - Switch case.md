A estrutura switch compara o valor de cada caso com o da variável sequencialmente, e sempre que encontra um valor correspondente, executa o código associado ao caso. Para evitar que as comparações continuem a ser executadas após um caso correspondente ter sido encontrado, acrescentamos o comando ***break*** no final de cada bloco de código. O comando **break**, quando executado, encerra a execução da estrutura onde ele se encontra.

Exemplo:

```java
char sigla = 'M';  
  
switch(sigla) {  
    case 'P':  
        System.out.println("PEQUENO");  
        break;  
    case 'M':  
        System.out.println("MÉDIO");  
        break;  
    case 'G':  
        System.out.println("GRANDE");  
        break;  
    default:  
        System.out.println("INDEFINIDO");  
        break;  
}
```

> **Atenção**
> 
> Se não tiver o **break**, todo o código abaixo será executado, o que pode atrapalhar ou facilitar em alguns casos.