A linguagem Java é composta por milhares de classes com as finalidades de, por exemplo, Classes de tipos de dados, representação de textos, números, datas, arquivos e diretórios, conexão com banco de dados, entre outros. Imagina todas essas classes existirem em um único nível de documentos? E as classes desenvolvidas por nós. imagina como ficaria este diretórios?

Para prevenir este acontecimento, a linguagem dispõe de um recurso que organiza as classes padrão e criadas por nós, que conhecemos como pacote ( package ). Os pacotes são subdiretórios a partir da pasta `src` do nosso projeto onde estão localizadas as classes da linguagem e novas que forem criadas para o projeto. Existem algumas convenções para a criação de pacotes já utilizados no mercado.

## Nomenclatura

Vamos imaginar que sua empresa se chama **Power Soft** e ela está desenvolvendo softwares comercial, governamental e um software livre ou de código aberto. Abaixo teríamos os pacotes sugeridos conforme tabela abaixo:

- **Comercial:** com.powersoft
- **Governamental:** gov.powersoft
- **Código aberto:** org.powersoft

Bem, acima já podemos perceber que existe uma definição para o uso do nome dos pacotes, porém podemos organizar ainda mais um pouco as nossas classes mediante a proposta de sua existência:

- **model:** classes que representam a camada e modelo da aplicação: Cliente, Pedido, NotaFiscal, Usuario.
- **repository:** classes ou interfaces que possuem a finalidade de interagir com tabelas no banco de dados: ClienteRepository.
- **service:** classes que contém regras de negócio do sistema: ClienteService possui o método validar o cpf do cliente cadastrado.
- **controller:** classes que possuem a finalidade de disponibilizar os nossos recursos da aplicação para outras aplicações via padrão http.
- **view:** classes que possuem alguma interação com a interface gráfica acessada pelo usuário.
- **util:** pacotes que contém classes utilitárias do sistema: FormatadorNumeroUtil, ValidadeUtil.

## Identificação

Uma das características de uma classe é a sua identificação, Cliente, NotaFiscal, TituloPagar, porém quando esta classe é organizada por pacotes, ela passa a ter duas identificações. O nome simples ( **próprio nome** ) e agora o nome qualificado ( **endereçamento do pacote + nome** ), exemplo: considere a classe `Usuario` que está endereçada no pacote `com.controle.acesso.model`, o nome qualificado desta classe é **`com.controle.acesso.model.Usuario`**.

## Package x Import

A localização de uma classe é definida pela palavra reservada `package`, logo, uma classe só contém uma definição de package no arquivo, sempre na primeira linha do código. Para a utilização de uma classe existente em outros pacotes, necessitamos realizar a importação das mesma, seguindo a recomendação abaixo:

```java
package

import ...

public class MinhaClasse {}
```