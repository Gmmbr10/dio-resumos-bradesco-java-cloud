O escopo é um ambiente onde uma variável pode ser acessada. No Java, o escopo das variáveis estará de acordo com o **bloco em que ela foi declarada**.

A variável é criada no primeiro acesso à ela, depois que o interpretador sair do seu bloco de código ela será inacessível. Com isso, a variável não pode ser manipulada fora de seu escopo.

Em uma Classe, podemos visualizar a diferença de escopos. Os atributos(variáveis) são declarados no corpo principal da Classe, podendo ser acessados por qualquer método.

Se você criar uma variável dentro de um método, essa variável será inacessível em outros métodos, limitando o seu uso apenas durante o corpo do método, dentro das chaves.