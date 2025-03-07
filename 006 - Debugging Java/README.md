# Debugging Java

Na programação, os erros são chamados de **bugs** e o processo de corrigi-los é chamado de depuração ou **debugging***.

Essa tarefa é trabalhosa, e dependendo do ambiente de desenvolvimento, linguagem utilizada, pode ser mais fácil ou mais difícil.

Existem dois grandes grupos de erros sendo eles:

### Erros de sintaxe

Um erro dentro das regras da linguagem:
1. Parênteses, chave, colchetes que abrem mas não fecham;
2. Duas instruções sem um ponto-e-vírgula entre elas;
3. Uma palavra-chave sendo usada numa posição incorreta.

### Erro de semântica

É um erro de lógica no código, sintaticamente correto porém, não faz o que se espera dele

1. Tentar dividir um número por zero ou uma string;
2. Atribuir o valor incoerente a um tipo de dado;
3. Tentar fechar um arquivo que nunca foi aberto

## Depuração/Debugging

As linguagens de alto nível tornam esse processo mais fácil, pois fornecem mais ferramentas para identificar erros, como o tratamento de exceções.

Os depuradores assumem o controle do tempo de execução de um programa, permitindo que você observe e controle a execução. Para isso, ele mostra a pilha do programa e permite que você vá em qualquer direção. Quando você está em um depurador, você obtêm uma imagem mais completa de um quadro de pilha do que quando você olha uma mensagem de log.

## Pilha de Execução

### Pilha de execução

Toda invocação de um método é empilhada em uma estrutura de dados que isola a área de memória de cada um. Quando um método termina, ele volta para o método que o invocou.

### Stack Trace

É a matriz onde encontramos a pilha de execução da exceção. Em outras palavras, podemos dizer que o rastreamento da pilha busca para a próxima linha onde a exceção pode surgir.

> **Atenção**
> 
> Sempre que formos ler essa stack, devemos ler de baixo para cima.