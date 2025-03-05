Quando executamos uma classe que contenha o método main, podemos passar um array [] de argumentos do tipo String. Dessa forma, podemos após definir a classe que será executada informar estes argumentos (parâmetros), por exemplo:

```bash
java NomeClasse argumentoUm argumentoDois
```

## Exemplo

```java
public class AboutMe {  
    public static void main (String [] args) {  
	    // os argumentos sempre começam pelo índice 0 (zero)
        String nome = args [0];  
        int idade = Integer.valueOf( args [1] );  // convertendo String para número
        double altura = Double.valueOf( args [2] );  
  
        System.out.println("Olá, meu nome é " + nome);  
        System.out.println("Tenho " + idade + " anos");  
        System.out.println("E tenho " + altura + "m de altura");  
    }  
}
```

### Executando
```bash
java AboutMe Nome idade altura
```