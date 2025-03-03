
```bash

git init

# mostrando a condição da árvore de trabalho
# pastas vazias não serão consideradas
# arquivos presentes no arquivo .gitignore, não aparecerão
git status

# adicionando o arquivo na preparação
git add nome-do-arquivo

# adicionando vários arquivos de uma vez
git add .

# salvar as alterações
git commit -m "mensagem do commit"

# mostrando histórico do repositório
git log

```

### .gitkeep

- Pastas com um arquivo `.gitkeep` são reconhecidas mesmo que vazias


### .gitignore

```txt

pasta/

arquivo.extensao

```