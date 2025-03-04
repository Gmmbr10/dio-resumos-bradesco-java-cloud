Todas as ações de um software são consideradas métodos.

Uma classe é definida por atributos e métodos. Vimos que atributos são, em sua maioria, variáveis. Já os métodos, por sua vez, são **funções** ou **sub-rotinas** disponíveis dentro de nossas classes.

## Convenção de nomeação de métodos

Eles não são obrigatórios, mas são fortemente recomendados pois facilitam o entendimento do código por outros programadores, quando trabalhado de forma colaborativa.

Quando seguimos essas convenções, tornamos o código mais legível para nós e para outras pessoas. Além disso, inserimos padrões em nossos projetos.

- Deve ser nomeado como verbo;
- Seguir o padrão camelCase, onde todas as letras são minúsculas com exceção da primeira letra da segunda palavra em diante.

## Métodos globais!?

Não existem métodos globais, todos os métodos são declarados dentro de uma classe.

## Critérios para definir um método

Quando iremos definir métodos em nossas classes? Podemos utilizar uma convenção estrutural para todos os métodos. Ela é definida pelos seguintes aspectos:

1. **Qual a proposta principal do método?** Você deve se perguntar várias vezes até entender qual a finalidade daquele método.
2. **Qual o tipo de retorno esperado após executar o método?** Você deve analisar e ver se o método será responsável por retornar algum valor ou não.

> **Caso o método não retorne nada, ele será representado pela palavra `void`**

3. **Quais parâmetros serão necessários para a execução do método?** Os métodos as vezes precisarão de argumentos como critérios para a execução.
4. **O método possui o risco de apresentar alguma exceção?** Exceções são comuns na execução de métodos, as vezes é necessário prever e tratar a possível existência de uma exceção.
5. **Qual a visibilidade do método?** Será necessário que o método seja visível para toda a aplicação, ou somente para ele mesmo, através de herança ou somente em pacotes.