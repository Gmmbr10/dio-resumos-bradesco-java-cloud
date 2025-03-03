
Em Java, `String` é uma classe que representa uma sequência de caracteres. Ela é usada para armazenar e manipular texto. Por exemplo, palavras, frases, ou qualquer outra sequência de caracteres podem ser armazenadas em uma `String`.

## Como declarar uma `String`?

```java
String nome = "Giovanne";
String nome = new String("Giovanne");
```

> A primeira forma é mais eficiente e, portanto, mais utilizada

## Como juntar duas `Strings`? (Concatenar)

```java
String nome = "Giovanne";  
String sobrenome = "Monteiro";  
String nomeCompleto = nome.concat(sobrenome);  
// ou  
String nomeCompleto = nome + " " + sobrenome;  
```

## Principais métodos

```java
int tamanhoNomeCompleto = nomeCompletoJunto.length();
// tamanho da String  
  
char letra = nomeCompletoJunto.charAt(0);
// retorna o caractere na posição indicada, inicia no 0  
  
String parteNome = nomeCompletoJunto.substring(0,8);
// retorna parte da string, remove parte da string  
  
String nomeMaiusculo = nome.toUpperCase();
// returna tudo em maiúscula  
  
String nomeMinusculo = nome.toLowerCase();
// retorna tudo em minúscula  
  
boolean mesmoNome = nome.equals("Monteiro");
// compara duas strings verificando se é igual ou não  
  
nome.trim();
// remove os espaços em branco no começo e no fim de uma string;  
  
String novoNome = nome.replace("va","be");
// substitui as ocorrências daquela parte por outra  
  
boolean contemLetraA = nome.contains("a");
// verifica se contém determinado conteúdo  
  
int posicaoLetraN = nome.indexOf("n");
// retorna a posição de determinada string  
  
String[] nomeCompletoArray = nomeCompletoSeparado.split(" ");
// divide a string naquela determinada ocorrência  
  
boolean nomeVazio = nome.isEmpty();
// retorna se está vazio  
  
int cep = 12345678;  
String cepTexto = String.valueOf(cep);
// converter outro tipo de dado para String
```