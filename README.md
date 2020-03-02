# RESUMÃO BÁSICO DE GIT    

#### Logar no Github

-- git config --global user.name "nome de usuario" --  
--git config --global user.email "email"  
--git config credential.helper store-- // configurar com a conta de usuario(para nao digitar a cada push)

#### Inicio

--git init-- // incicializar um repositorio local  
--touch--    // criar um arquivo local
--git clone URL-do-repositorio-do-github-- // clonar um repositorio do github

#### Administrar Mudancas

--git status-- // ver o estado das mudancas feitas  
--git add .-- // adicionar as mudancas feitas na branch em que o usuario esta  
--git add nome-de-arquivo // adicionar um arquivo em especifico naquela branch  
--git commit -m "..." // comitar alteracoes, deixando uma mensagem de descricao do commit  
--git push -u origin nome-da-branch-- // dar o primeiro push de uma branch  
--git push-- // push comum  
--git merge // unir as branch's

#### Verificar alteracoes

--git show-- // mostrar a ultima alteracao feita  
--git log-- // mostrar todas as alteracoes feitas. obs: sair do git log com "q"  
--git show codigo-da-alteracao-- // ver uma alteracao especifica (codigo da alteracao no git log)  
--git remote -v-- // checar repositorios remotos

#### Branch's

--git branch nome-da-branch-- // criar uma branch  
--git checkout nome-da-branch-- // entrar em uma branch  
--git branch -r-- // listar as branch's do repositorio remoto  
--git branch-- // mostrar as branch's do repositorio local e em qual o usuario esta atualmente  
--git branch -D nome-da-branch // deletar uma branch localmente  
--git push origin --delete nome-da-branch // deletar uma branch remotamente

#### Atualizar

--git pull-- // atualizar repositorio local a partir do remoto  

#### Modificacoes

--git checkout codigo-da-modificacao-- // voltar uma modificacao especifica (codigo da modi. no git log)
