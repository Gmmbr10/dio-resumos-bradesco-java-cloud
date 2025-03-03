```bash

# removendo o git de uma pasta
rm -rf .git

# revertendo alterações em arquivos
git restore nome-do-arquivo

# alterar mensagem do último commit
git commit --amend -m "nova mensagem"

# digitando o comando abaixo e pressionando 'enter', será aberto um editor de texto para que você possa alterar o texto manualmente
git commit --amend

# histórico detalhado dos commits
git reflog

```

## Voltando um commit

### Tipos

- **Soft:** pega os arquivos do commit e adiciona na árvore de preparação
- **Mixed:** pega os arquivos mas não adiciona na árvore de preparação
- **Hard:** remove todos os arquivos que não estavam no commit

```bash

git reset --tipo hash-do-commit

```


### Tirando arquivos da árvore de preparação

```bash

git reset nome-do-arquivo
# ou
git restore --staged nome-do-arquivo

```