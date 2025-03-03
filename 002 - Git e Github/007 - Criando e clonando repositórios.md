Existem duas formas de ter um repositório Git:

1. Transformando um diretório local que não está sob controle de versão

2. Clonando um repositório Git existente

### Transformando um diretório local

```bash

# entra na pasta

# transformando o repositório
git init

```

### Clonando o repositório

```bash

# clonando apenas
git clone link

# (opcional) clonando e renomeando o diretório
git clone link nome-do-diretorio-local

# selecionando apenas uma branch específica, caso o repositório tenha várias branchs
git clone link --branch nome-da-branch --single-branch

```

```bash

# mostrando quais repositórios web o repositório está conectado
git remote -v

# adicionando um repositório remoto
# dentro do repositório
git remote add origin link-repositorio-web

```