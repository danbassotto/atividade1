# atividade1

git init 

git add README.md

git commit -m "atividade1"

git branch- m master

git add origin git@github.com:danbassotto/atividade1.git

git push -u origin master


----------------------- new branch usuario1 --------------------------

git checkout -b usuario1

> alterar bloco de notas "alteração atividade - usuario1"

git add alteracoes-linhasdecodigo.txt

git commit -m "alteração usuário1"

git push -u origin usuario1

----------------------- new branch usuario2 --------------------------

git checkout -b usuario2

> alterar bloco de notas "alteração atividade - usuario2"

git add alteracoes-linhasdecodigo.txt

git commit -m "alteração usuário2"

git push -u origin usuario2

usuario2



>>>> MERGE EFETUADO (merge-users.txt)

git checkout master

git merge usuario1

git merge usuario2

---------CONFLITO APRESENTADO----------

>Exclusão de conflitos

git add alteracoes-linhasdecodigo.txt

git commit -m "resolução de conflitos"

-------Esqueci de excluir uma parte do conflito"

> realizo a exclusão

git add alteracoes-linhasdecodigo.txt

git commit -m "resolução de conflitos (correção)"

git push -u origin master





>>>> ADIÇÃO DE TAGS (add-tag.txt)

----------------------Adição de tag----------------------

git tag -a atividade1 -m "Atividade 1 SENAI"

git tag

git tag show atividade1

git push origin --tags



------------Finalização de atividade---------------

git add .

git commit -m "finalizando atividade1" 

git push -u origin master