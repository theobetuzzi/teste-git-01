```
/*
GITHUB

--Geral--
git status
git remote -v (conferir)
git config
git log: mostra todos commits e infos
git show código-identificador-commit (inspeciona o commit)
git show (inspeciona o último commit)
fork é fazer uma coópia para seu GitHub

.............................................
--Inicializar repositório local--
git init
git add nome do aquivo || git add . (todos os arquivos)
git reset: reverte o git add
git commit -m "nome commit"
git commit -am "nome commit" (atalho para adicionar e commitar juntos)
git branch -M "novo nome da branch"

.............................................
--Branch Feature(caminho aternativo)--
git branch feature/nome-da-branch (criar)
git checkout feature/nome-da-branch (se move para ela)
git checkout -b nome-nova-branch (criar e já migra para nova branch)
git checkout master (volta para a principal)
git merge featute/nome-da-branch (une a feature a master)

git branch (mostra todas a branchs criadas)
git branch -D feature/nome-da-branch (deleta branch)

.............................................
--Enviar para GitHub--
criar repositório vazio no site 
git remote add origin URL
git push -U origin nomeDaBranch

.............................................
--Pegar do GitHub--
git clone URL

.............................................
--Voltar a um commit--
git checkout código-identificador-commit 
git status
faça outro commit e push

.............................................
--Atualizar repositório local--
git pull 

.............................................
--Git Ignore--
.gitignore (escreve nome de arquivos e pastas que devem ser ignorados)

*/
```