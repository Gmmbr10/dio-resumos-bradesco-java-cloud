## O que é uma branch?

Nada mais é do que uma ramificação do projeto, um "Novo universo".

Quando você cria uma nova branch, ela inicia a partir do último commit realizado na branch estava usando e acaba por trabalhar de forma independente a outra branch.

Usada para evitar conflitos entre as diferentes alterações presentes durante o desenvolvimento do projeto.

## Manipulando as branches

```bash

# criando uma nova branch
git checkout -b nome-da-branch

# trocando de branch
git checkout nome-da-branch

# mesclando branches
git merge nome-da-branch

# listando as branches
git branch

# deletando a branch
git branch -d nome-da-branch

```

## Tratando conflitos

As vezes você e seu amigo editaram a mesma linha de código, o que pode gerar conflito

### O que fazer?

Baixe as alterações antes de enviar para o repositório remoto.