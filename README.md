# RESUMÃO BÁSICO DE GIT    

#### Logar no Github

<<<<<<< HEAD
__git config --global user.name "nome de usuario"__  
__git config --global user.email "email"__  
__git config credential.helper store__ // configurar com a conta de usuario(para nao digitar a cada push)
=======
-- git config --global user.name "nome de usuario" --  
--git config --global user.email "email"  
--git config credential.helper store-- // configurar com a conta de usuario(para nao digitar a cada push)
>>>>>>> 545ce52ba065f21b8fffc305b925a7442a6cc320

#### Inicio

__git init__ // incicializar um repositorio local  
__touch__    // criar um arquivo local
__git clone URL-do-repositorio-do-github__ // clonar um repositorio do github

#### Administrar Mudancas

__git status__ // ver o estado das mudancas feitas  
__git add .__ // adicionar as mudancas feitas na branch em que o usuario esta  
__git add nome-de-arquivo__ // adicionar um arquivo em especifico naquela branch  
__git commit -m "..."__ // comitar alteracoes, deixando uma mensagem de descricao do commit  
__git push -u origin nome-da-branch__ // dar o primeiro push de uma branch  
__git push__ // push comum  
__git merge__ // unir as branch's

#### Verificar alteracoes

__git show__ // mostrar a ultima alteracao feita  
__git log__ // mostrar todas as alteracoes feitas. obs: sair do git log com "q"  
__git show codigo-da-alteracao__ // ver uma alteracao especifica (codigo da alteracao no git log)  
__git remote -v__ // checar repositorios remotos

#### Branch's

__git branch nome-da-branch__ // criar uma branch  
__git checkout nome-da-branch__ // entrar em uma branch  
__git branch -r__ // listar as branch's do repositorio remoto  
__git branch__ // mostrar as branch's do repositorio local e em qual o usuario esta atualmente  
__git branch -D nome-da-branch // deletar uma branch localmente  
__git push origin __delete nome-da-branch // deletar uma branch remotamente

#### Atualizar

__git pull__ // atualizar repositorio local a partir do remoto  

#### Modificacoes

__git checkout codigo-da-modificacao__ // voltar uma modificacao especifica (codigo da modi. no git log)
