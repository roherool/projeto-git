# Comandos essenciais do GIT

## Iniciando o GIT

### Iniciar o GIT dentro da pasta do projeto: 
git init

### Adicionar arquivo no GIT:
git add .gitignore

### Visualizar arquivos adicionados:
git status

### Visualizar o LOG do GIT no local e remoto:
git log

## Adicionando os arquivos ao COMMIT

### Adicionar arquivos no GIT
- git add . (o ponto define todos)
- git add [nome-do-arquivo] (Adicionar um arquivo específico)

### Criar o ponto de restauração:
git commit -m "chore: Commit inicial"
- a) chore = Sugestão de uso para o sistema geral
- b) fix = Sugestão de uso quando for para conserto de bugs
- c) feature = Sugestão de uso quando for para funcionalidade nova

## Preparando os commits para envio

### Preparar o COMMIT para envio:
git remote add origin [url-destino-github]

### Excluir um COMMIT para envio:
git remote rm origin

## Publicando o commit no GIT

### Enviar o COMMIT por PUSH: 
- git push -u origin master (Usar o -u origin master no primeiro push)
- git push (Somente se já teve o primeiro push)

## Trabalhando com BRANCH no GIT

### Visualizando os BRACHS existente:
git branch

### Criar um BRANCH novo no GIT:
git branch [nome-do-branch]
git checkout -b [nome-do-branch]  ou [feature/nome-do-branch]

### Trocar de ramificação ou branch:
git checkout [branch-destino]

### Excluir uma BRANCH do GIT:
git branch -d [nome-do-branch]

### Unificar arquivos de 2 ou mais Branchs
git rebase [nome-do-arquivo]

## Trabalhando com MERGE

### Fazer o MERGE dos BRANCHS:
git merge [branch-de-origem]
