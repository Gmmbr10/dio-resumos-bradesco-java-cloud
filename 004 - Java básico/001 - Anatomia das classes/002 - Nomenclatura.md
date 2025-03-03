## Padrões de nomenclatura

- **Arquivo .java:** Todo arquivo .java deve começar com letra maiúscula. Se a palavra for composta, a segunda palavra deve também começar com letra maiúscula, exemplo:
`Calculadora.java , CalculadoraCientifica.java`

- **Nome da classe no arquivo:** A classe existente no arquivo, deve possuir o mesmo nome do arquivo.java, exemplo:
```java
// arquivo Calculadora.java

public class Calculadora {

}
```

- **Nome de variável:** toda a variável deve ter letra minúscula, caso tenha palavra composta, a primeira letra das próximas palavras deve ser maiúscula, por exemplo: `ano` e `anoFabricacao`. O nome desse padrão é `camelCase`.

- **Nome de constantes:** todas as constantes devem ser escritas inteiramente por letras maiúsculas e palavras compostas devem ser separadas por underline `_`, por exemplo:
```java
String BR = "Brasil"
double PI = 3.14
int ESTADOS_BRASILEIROS = 27
int ANO_2000 = 2000
```

> **Evitando problemas**
> 
> Para evitar que alterem os valores podemos fazer o seguinte:
> 
> ``` java
> final String BR = "Brasil"
> ```

> **Recomendações:**
> 
> Quando declaramos uma variável, podemos utilizar caracteres, números e símbolos, mas temos regras para isso
>
> - Deve conter apenas letras, _ (underline), $ ou os números de 0 a 9
> - Deve começar com letra, _ (underline) ou $, nunca por números
> - Iniciar com letra minúscula (boas práticas)
> - Não pode conter espaços
> - Não pode user palavras chave da linguagem
> - O nome deve ser único no escopo

