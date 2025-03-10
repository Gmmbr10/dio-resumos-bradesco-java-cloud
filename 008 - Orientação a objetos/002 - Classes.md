Toda a estrutura de código na linguagem Java é distribuído em arquivos **`.java`** denominados de **classes**.

As classes existentes em nosso projeto serão composta por:
**Identificador, Características e Comportamentos.**

- **Classe (*class*):** A estrutura e ou representação que direciona a criação dos objetos de mesmo tipo
- **Identificador (*identity*):** Propósito existencial aos objetos que serão criados.
- **Características (*states*):** Também conhecido como **atributos** ou **propriedades**, é toda informação que representa o estado do objeto.
- **Comportamentos (*behavior*):** Também conhecido como **ações** ou **métodos**, é toda parte comportamental que um objeto dispõe.
- **Instanciar (*new*):** É o ato de criar um objeto a partir de uma estrutura definida em uma classe.

> **Atenção**
> 
> Pense que, primeiro você molda, depois você constrói.

Seguindo algumas convenções, as nossas classes são classificadas como:

- **Classe de modelo (model):** classes que representam estruturas de domínio da aplicação. Exemplo: Cliente, Pedido, Nota Fiscal, etc.
- **Classe de serviço (service):** classes que contém regras de negócio e validação de nosso sistema.
- **Classe de repositório (repository):** classes que contém uma integração com banco de dados.
- **Classe de controle (controller):** classes que possuem a finalidade de disponibilizar alguma comunicação externa à nossa aplicação, tipo http web ou webservice.
- **Classe utilitária (util):** classe que contém recursos comuns à toda nossa aplicação.