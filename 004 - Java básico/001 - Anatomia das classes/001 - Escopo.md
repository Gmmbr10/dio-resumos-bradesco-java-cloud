Escrever código nada mais é do que escrever palavras pré-definidas pela linguagem na intenção de determinar nome de arquivo, classes, atributos e métodos;

É comum misturar as linguagens durante a escrita do código, o que é da linguagem em inglês e nome de atributos, métodos e classes em português;
- Mas nem sempre vai ser assim, alguns casos podem ser na mesma linguagem

## Como iremos escrever os códigos em java?

Todas as classes ficam na pasta `src`.

O nome da classe é o mesmo que o nome do arquivo.

```java
public class MinhaClasse {
	// seu código aqui
	// corpo da classe
}
```

Neste caso será: `MinhaClasse.java`

### Dica
- Coloque nomes sugestivos na sua classe
- Defina um diretório padrão para os projetos

## Convenções

1. Toda classe, a primeira letra de cada palavra será em letra maiúscula;

## O que escrever no código?

### A classe é executável ( ela vai iniciar o projeto ) ?

Necessita ter um método principal, chamado `main`.

Para declarar este método precisamos fazer o seguinte:

```java
public static void main(String[] args) {
	// corpo do método
}
```

O java possuí classes nativas, algumas delas possuem funções específicas.

Exibir texto:

```java
System.out.print("Texto a ser exibido");
```