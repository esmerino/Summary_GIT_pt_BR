# SUMMARY GIT :pt_BR

## Criando um novo repositório.

```ruby

git init .

```

## Obtendo um repositório.

```ruby

git clone /caminho/do/repositório
git clone usuário@servidor:/caminho/do/repositório

```

## Adicionar e Confirmar

### Adicionar

```ruby

git add <arquivo>
git add *

```

### Confirmar

```ruby

git commit -m "comentário das alterações"

```

## Enviando Alterações

```ruby

git push -u origin master

```
## Conectar a um repositório remoto

```ruby

git remote add <origin> servidor

```

## Ramificando

### Criando um novo branch chamando "criando_um_branch"

```ruby

git checkout -b criando_um_branch

```

### Retornando par o mater

```ruby

git checkout master

```

### Removendo o branch "criando_um_branch"

```ruby

git branch -d criando_um_branch

```

### Enviando o branch para o repositório remoto

```ruby

git push origin <criando_um_branch>

```

## Atualizar e Mesclar

### Atualizar o repositório local com a mais nova versão e mesclar a alteração remota

```ruby

git pull

```

### Atualizar o repositório local com a mais nova versão e mesclar a alteração remota de outro branch

```ruby

git merge <branch>

```

### Pré-visualizar as alterações antes de fazer um merger entre branchs

```ruby

git diff <branch origem> <branch destino>

```

## Rotulando/Tags

```ruby

git tag -a v1 -m"Nova tag para analisar um versão"

```

## Sobrescrever alterações locais

### Sobrescrever

```ruby

git checkout -- <arquivo>

```

### Remover todas as alterações e commits locais

```ruby

git fetch origin
git reset --hard origin/master

```

## Dicas úteis

### Git com saída colorida

```ruby

git config color.ui true

```

### Exibir log em uma linha por commit

```ruby

git config format.pretty oneline

```

### Inclusões interativas

```ruby

git add -i

```

