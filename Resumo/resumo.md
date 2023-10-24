# 📄 Resumo

## 🔨 Criando repositórios

```
$ git remote add origin URL
$ git clone URL nome-do-diretorio-local <muda o nome>
$ git clone URL --branch nome-da-branch --single-branch
$ touch arquivo-novo
$ git commit -m "descrição"
$ git log
$ echo pasta/ > .gitignore  // faz o git ignorar a pasta

.gitkeep // git reconhece arquivo vazio

$ git add . // adiciona todos os arquivos-não-listados

```

## ⛏ Desfazendo alterações

```
$ rm -rf .git // desfaz repositório
$ git restore <nome do arquivo> // elimina as mudanças feitas na árvore de trabalho
$ git commit --amend -m "<nova mensagem>" // muda a mensagem do último commit
$ git commit --amend // abre o editor
esc :wq // sai do editor
$ git reset --soft <hash do commit> // passa o commit pra área de preparação
$ git reset --mixed <hash do commit> // adicionou os arquivos na área de trabalho
$ git reset --hard <hash do commit> // apaga os arquivos do commit
$ git reflog // histórico detalhado dos commits
$ git restore --staged // remove arquivos da área de preparação

```

## 📡 Enviando e Baixando Alterações com o Repositório Remoto 

```
$ git push // manda as alterações do repositório local para o remoto
$ git pull // passa as alterações do repositório remoto para o local

```

## 🖇 Trabalhando com Branches

```
$ git checkout -b <nome da branch> // cria uma nova branch
$ git checkout <nome da branch> // muda para uma branch existente
$ git branch -v // mostra o último commit de todas as branchs
$ git merge <nome da branch> // mescla a branch com a main
$ git branch // lista as branches do repositório
$ git branch -d <nome da branch> // remove a branch

```

## Comandos úteis do dia-a-dia

```
$ git fetch // baixa as alterações do repositório remoto
$ git diff <branch1/branch2> // mostra as diferenças entre as branches
$ git clone URL --branch <nome da branch> --single-branch
$ git stash // arquiva a modificação
$ git stash list // lista as modificações
$ git stash pop // remove a última modificação
$ git stash apply // traz a modificação

```

## 🎁 Materiais de apoio

-[Repositório do Github](https://github.com/elidianaandrade/dio-curso-git-github)