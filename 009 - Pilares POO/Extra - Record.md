Em Java, records são uma funcionalidade introduzida no Java 14 (como preview) e oficialmente lançada no Java 16. Eles fornecem uma maneira concisa e imutável de definir classes que servem principalmente para armazenar dados.

## Características

1. **Imutabilidade:** Os atributos são automaticamente `final`, impedindo modificações após a criação do objeto.
2. **Definição simplificada:** O compilador gera automaticamente o construtor, métodos getter, equals(), hashCode() e toString().
3. **Uso recomendado:** Ideal para modelar dados imutáveis, como DTOs (Data Transfer Objects).

### Exemplo de um Record:

```java
public record Pessoa(String nome, int idade) {}
```

O código acima equivale a uma classe tradicional com **construtor, getters, `equals()`, `hashCode()` e `toString()`**, sem necessidade de implementação manual.

### Exemplo de uso

```java
Pessoa p = new Pessoa("João", 30);
System.out.println(p.nome()); // João
System.out.println(p.idade()); // 30
```

