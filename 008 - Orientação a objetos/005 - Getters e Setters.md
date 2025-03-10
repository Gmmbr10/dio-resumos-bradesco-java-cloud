Seguindo a convenção Java Beans

Os métodos "Getters" e "Setters" são utilizados para buscar valores de atributos ou definir novos valores de atributos de instâncias de classes.

O método **Getter** retorna o valor do atributo especificado.
O método **Setter** define outro novo valor para o atributo especificado.

Seguindo a convenção Java Beans, uma classe que contém esta estrutura de estados deverá seguir as regras abaixo:

- Os atributos precisam ter o modificador de acesso `private`;
- Como agora os atributos estarão somente a nível de classe, precisaremos dos métodos **getX** e **setX**;
- O método **get** é responsável por obter o valor atual do atributo, logo ele precisa ser  `public` e retornar um tipo correspondente ao valor;
- O método  **set** é responsável por definir ou modificar o valor de um atributo em um objeto, logo ele também precisa ser `public`, receber um parâmetro do mesmo tipo da variável mas não retorna nenhum valor `void`.

> **Observação**
> 
> Esse padrão se tornou importante porque antes de realizar algum tipo de atribuição, nós podemos validar e verificar se os dados estão de acordo com as regras.

Exemplo:

```java
public class Pessoa {  
    private String nome;  
    private String cpf;  
    private String endereco;  
  
    public String getNome() {  
        return nome;  
    }  
  
    public void setNome(String nome) {  
        this.nome = nome;  
    }  
  
    public String getCpf() {  
        return cpf;  
    }  
  
    public void setCpf(String cpf) {  
        this.cpf = cpf;  
    }  
  
    public String getEndereco() {  
        return endereco;  
    }  
  
    public void setEndereco(String endereco) {  
        this.endereco = endereco;  
    }  
}
```