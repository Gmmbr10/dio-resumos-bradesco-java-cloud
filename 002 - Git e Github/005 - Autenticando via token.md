- Com um repositório já criado, ou criando um

```bash

git clone #link do repositório

# você falhará miseravelmente

```

- Github -> Settings -> Developer settings -> Personal access tokens -> Tokens (classics)
- Coloca um nome para o token no note
- Coloque um tempo limite no token
- Você pode limitar os acessos do token
	- Defina o `repo` como ativo para poder clonar o repositório

```txt

Depois que você sair da página, o token irá sumir!!!

Você pode ver os tokens existentes, mas não os códigos dos tokens!

```

### Manter a credencial salva no seu computador

- Isso lhe permite clonar os repositórios sem precisar colocar as credenciais novamente

```bash

git config --global credential.helper cache

git config --global credential.helper 'store --file ~/.my-credential'

```