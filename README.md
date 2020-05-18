# projeto-git

# INICIANDO O GIT

## Iniciar o GIT dentro da pasta do projeto: 
git init

## Adicionar arquivo no GIT:
git add .gitignore

3. Visualizar arquivos adicionados:
git status

4. Visualizar o LOG do GIT no local e remoto:
git log

ADICIONANDO OS ARQUIVOS AO COMMIT

5. Adicionar arquivos no GIT:
git add . (o ponto define todos)
git add + arquivo (Adiciona um arquivo específico)

6. Criar o ponto de restauração:
git commit -m "chore: Commit inicial"
a) chore = usado para o sistema geral
b) fix = usado quando for para conserto de bug
c) feature = usado quando for para funcionalidade nova

PREPARANDO OS COMMITS PARA ENVIO

7. Preparar o COMMIT para envio:
git remote add origin + (destino do arquivo no git)

8. Excluir um COMMIT para envio:
git remote rm origin

PUBLICANDO O COMMIT NO GIT

9. Enviar o COMMIT por PUSH: 
git push -u origin master (Usar o -u origin master no primeiro push)

git push (Somente se já teve o primeiro push)

TRABALHANDO COM BRANCHS NO GIT

10. Visualizando os BRACHS existente:
git branch

11. Criar uma BRANCH nova no GIT:
git branch [nome-do-branch]
git checkout -b [nome-do-branch]  ou [feature/nome-do-branch]

12. Trocar de ramificação ou branch:
git checkout [branch-destino]

13. Excluir uma BRANCH do GIT:
git branch -d [nome-do-branch]

14. Unificar arquivos de 2 ou mais BRANCHS
git rebase [nome-do-arquivo]

TRABALHANDO COM MERGE

15. Fazer o MERGE dos BRANCHS:
git merge [branch-de-origem]
