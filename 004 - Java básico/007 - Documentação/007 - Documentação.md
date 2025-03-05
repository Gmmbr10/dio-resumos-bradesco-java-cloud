Ela possuí toda a explicação da linguagem ou framework sem nem precisar escrever código. Importante para que se entenda ou aprenda determinado método ou biblioteca da linguagem.

## Java Documentation | Tags

As tags são as informações que temos através de classes documentadas na linguagem.

O Java Documentation é composto por tags que representam dados importantes para o entendimento de determinada classe e o seu conjunto de métodos e atributos. Veja na tabela abaixo:

| Tag      | Descrição                                              |
| -------- | ------------------------------------------------------ |
| @autor   | Autor / Criador                                        |
| @version | Versão do recurso disponibilizado                      |
| @since   | Versão / Data de início da disponibilização do recurso |
| @param   | Descrição dos parâmetros dos métodos criados           |
| @return  | Definição do tipo de retorno de um método              |
| @throws  | Se o método lança alguma exceção                       |

> Você pode, durante a documentação, utilizar tags `HTML`

## Tipos de comentário

```java
// comentário em uma linha

/* Este
* Comentário é de linhas multiplas
* Posso usar quantas linhas eu quiser
*/

/** Documentação
* Este comentário é para documentação
* Servindo para realizar as documentações de:
* - classes
* - métodos
* - atributos
*/

```

## JavaDoc
Este é um recurso do Java que permite que você gere uma documentação do seu código executando apenas um comando:

```bash
javadoc -encoding UTF-8 -docencoding ISO-8859-1 -d ./docs src/*.java
```