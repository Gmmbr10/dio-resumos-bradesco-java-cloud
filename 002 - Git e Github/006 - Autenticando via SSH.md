- Uma forma segura e criptografada de conexão
- Conexão entre chave publica e privada

1. Gere um código ssh

```bash

ssh-gen ed25519 -C 'email@example'

# Enter

# Coloca uma senha

```

2. Inicia o agente ssh

```bash

eval "$(ssh-agent -s)"

```

3. Adiciona a chave ssh privada

```bash

ssh-add ~/.ssh/id_ed25519

# Coloca a senha

```

4. Adiciona uma nova ssh no github

- Github -> Settings -> SSH and GPG keys
- Título da chave
- Tipo da chave
- Cola a chave pública

```bash

# como pegar a chave ssh pública
cat ~/.ssh/id_ed25519.pub

```