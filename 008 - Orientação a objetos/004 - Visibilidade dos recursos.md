## Modificadores

Em java, utilizamos três palavras reservadas e um conceito default ( sem nenhuma palavra reservada ) para definir os quatro tipos de visibilidade de atributos, métodos e até mesmo classes no que se refere ao acesso por outras classes. Iremos ilustrar do mais visível ao mais restrito tipo de visibilidade nos arquivos em nosso projeto.

### Modificador public

Como o próprio nome representa, quando nossa classe, método e atributo é definido como public, qualquer outra classe em qualquer outro pacote pode visualizar tais recursos.

### Modificador default

O modificador `default` está fortemente associado a organização das classes por pacotes, algumas implementações não precisam estar disponíveis por todo o projeto, e este modificador de acesso restringe a visibilidade por pacotes.

> É quando não tem nenhuma palavra antes do tipo do retorno

### Modificador private

O modificador `private` impede que outras classes acessem aquele determinado método. Independente do pacote em que ele está. Apenas a própria classe tem acesso.

### Modificador protected

O modificador `protected` assegura que somente classes filhas ou de mesmo pacote acesse seus recursos de mesmo acesso.