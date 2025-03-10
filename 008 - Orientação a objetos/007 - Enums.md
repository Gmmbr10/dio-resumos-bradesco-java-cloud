Enum é um tipo especial de classe onde os objetos são previamente criados, imutáveis e disponíveis por toda aplicação.

Usamos Enum quando o nosso modelo de negócio contém objetos de mesmo contexto que já existem de pré-estabelecida com a certeza de não haver tanta alteração de valores.

Exemplo

**Estado civil:** Solteiro, Casado, Divorciado, Viúvo
**Grau de escolaridade:** Analfabeto, Fundamental, Médio, Superior

Enquanto que uma constante é uma variável de tipo com valor imutável, um Enum é um conjunto de objetos já pré-definidos na aplicação.

Como um Enum é um conjunto de objetos, logo, estes objetos podem conter atributos e métodos. Veja o exemplo de um Enum para disponibilizar estados brasileiros, contendo informações como: Nome, Sigla e um método para pegar o nome de cada estado.

### Exemplo de criação de Enum

```java
public enum EstadosBrasileiros {  
	// valores pré-definidos
    SAO_PAULO("SP","São Paulo"),  
    RIO_JANEIRO("RJ","Rio de Janeiro"),  
    CEARA("CE","Ceará"),  
    ;  

	// estrutura do objeto enum
    private String nome;  
    private String sigla;  
  
    private EstadosBrasileiros(String sigla, String nome) {  
        this.sigla = sigla;  
        this.nome = nome;  
    }  
  
    public String getNome() {  
        return nome;  
    }  
  
    public String getSigla() {  
        return sigla;  
    }  
}
```

### Exemplo de uso de Enum

```java
public class SistemaIbge {  
    public static void main(String[] args) {  
	    // iterando sobre o enum
        for (EstadosBrasileiros estado : EstadosBrasileiros.values()) {  
            System.out.println(estado.getSigla() + " - " + estado.getNome());  
        }  

		// pegando um dado da lista do enum
        EstadosBrasileiros estadoBrasileiro = EstadosBrasileiros.SAO_PAULO;  
  
        System.out.println(estadoBrasileiro.getNome());  
    }  
}
```