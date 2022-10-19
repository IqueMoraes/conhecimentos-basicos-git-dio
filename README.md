# Conhecimentos básicos do Git
Este repositório foi criado para entrega da avaliação dos conhecimentos básicos da tecnologia Git no Bootcamp **Geração Tech Unimed-BH - Ciência de Dados**.  
  
  
## Etapas realizadas neste repositório

### Etapa 1
Aberta conta pessoal na plataforma [GitHub](https://github.com/).

### Etapa 2
Gerada chave SSH local.

### Etapa 3
Configurada chave e permissões no perfil do GitHub.

### Etapa 4
Aberto o repositório remoto no [GitHub](https://github.com/IqueMoraes/conhecimentos-basicos-git-dio).

### Etapa 5
Aberto um diretório local.  
Clonado o repositório remoto no diretório local com o comando:
> git clone git@github.com:IqueMoraes/conhecimentos-basicos-git-dio.git

### Etapa 6
Editado pela primeira vez o arquivo _README.md_, incluindo breve descrição deste repositório.  
Adicionado o arquivo ao _stage_ para registro de alteração com o comando:
> git add .

Realizado o _commit_ consolidando a alteração com o comando:
> git commit -m "Create repo"

Atualizado repositório remoto com o comando:
> git push origin main


### Etapa 7
Aberta nova branch para alterar o arquivo _README.md_ com o comando:
> git checkout -b "feat/start-readme"

### Etapa 8
Digitadas as etapas realizadas até o momento no arquivo _README.md_.
Repetida a etapa 6 com os comandos:
>git add .
>git commit -m "update readme file"
>git push -u origin feat/start-readme


### Etapa 9
Alterada área de trabalho para _main_ com o comando:
> git checkout main

### Etapa 10
Incluída a _branch_ 'feat/start-readme' na _main_ com o comando:
> git merge feat/start-readme

### Etapa 11
Adicionada alterações ao _stage_ com os comandos da etapa 6.
> git add .  
> git commit -m "merge update readme branch into main"

### Etapa 12
Incluída as alterações no repositório remoto com os comandos:
> git add .  
> git commit -m "add 'etapa 12' update remote repo"
> git push




