Palavras reservadas são identificadores de uma linguagem que já possuem uma finalidade, impossibilitando nomear variáveis, classes, métodos ou atributos.

No Java, temos 52 palavras reservadas. Todas essas palavras são classificadas e escritas em minúsculo, sendo identificada por determinada cor nas IDE's.

## Lista de palavras reservadas agrupadas e suas funções

### Controle de pacotes
**Import:** importa pacotes ou classes para o código

**package:** específica a que pacote todas as classe de um arquivo pertencem

### Modificadores de acesso
**public:** acesso de qualquer classe

**private:** acesso apenas em uma classe

**protected:** acesso por classes no mesmo pacote e subclasses

### Tipos de dados primitivos
**boolean:** um valor que indica falso ou verdadeiro

**byte:** um valor inteiro de 8 bits (signed)

**char:** um character unicode (16-bits unsigned)

**double:** um número de ponto flutuante de 64 bits (signed)

**float:** um número de ponto flutuante de 32 bits (signed)

**int:** um inteiro de 32 bits (signed)

**long:** um inteiro de 64 bits (signed)

**short:** um inteiro de 32 bits (signed)

**void:** indica um método sem retorno **de valor**

### Modificadores de classes, variáveis ou métodos
**abstract:** classes que não podem ser instanciada ou método que precisa ser implementado por uma subclasse não abstrata

**class:** especifica uma classe

**extends:** indica uma superclasse que a subclasse está estendendo

**final:** impossibilita que uma classe seja estendida, que um método seja sobrescrito ou que uma variável seja reinicializada

**implements:** indica a interface que uma classe irá implementar

**interface:** especifica uma interface

***native:*** indica que um método está escrito em uma linguagem dependente de plataforma, como o C

**new:** instancia um novo objeto, chamando seu construtor

**static:** faz um método ou variável pertencer à classe ao invés de às instâncias

***strictfp:*** usada em frente a um método ou classe para indicar que os números de ponto flutuante seguirão as regras de ponto flutuante em todas as expressões

**synchronized:** indica que um método só pode ser acessado por uma thread de cada vez

**transient:** impede a serialização de campos

***volatile:*** indica que uma variável pode ser alterada durante o uso de threads

### Controle de fluxo dentro de um bloco de código
**break:** sai do bloco de código em que ele está

**case:** executa um bloco de código dependendo do teste do switch

**continue:** pula a execução do código que viria após esse comando e vai para a próxima passagem do loop