Anteriormente, precisávamos passar os dados via argumentos, mas há outra forma de passar dados para o nosso sistema. Ele se chama **Scanner** e possuí a finalidade de facilitar as entradas de dados e deixa-las mais seguras.

Através da classe Scanner podemos receber os dados. Para usa-la devemos importar ela, e fazemos da seguinte maneira:

```java
import java.util.Locale;  
import java.util.Scanner;  
  
public class AboutMe {  
    public static void main (String [] args) {  
        // criando o objeto scanner  
        Scanner entradaDados = new Scanner(System.in).useLocale(Locale.US);  
  
        System.out.println("Digite seu nome: ");  
        String nome = entradaDados.next();  
  
        System.out.println("Digite sua altura: ");  
        double altura = entradaDados.nextDouble();  
  
        System.out.println("Digite sua idade: ");  
        int idade = entradaDados.nextInt();  
    }  
}
```

> **Atenção**
> 
> O `Locale` é usado para que possamos utilizar padrões de determinadas localidades.