![enter image description here](http://capitalcode.com.br/curso-proj/1.jpg)![
](http://capitalcode.com.br/curso-proj/2.jpg)
![
](http://capitalcode.com.br/curso-proj/3.jpg)
![
](http://capitalcode.com.br/curso-proj/4.jpg)
![
](http://capitalcode.com.br/curso-proj/5.jpg)
![
](http://capitalcode.com.br/curso-proj/6.jpg)
![
](http://capitalcode.com.br/curso-proj/7.jpg)
![
](http://capitalcode.com.br/curso-proj/8.jpg)
![
](http://capitalcode.com.br/curso-proj/9.jpg)
![
](http://capitalcode.com.br/curso-proj/10.jpg)
![
](http://capitalcode.com.br/curso-proj/11.jpg)

## Configurando Usuário Global

    git config --global user.name "Capital Code"
   

## Configurando E-mail Global

    git config --global user.email "cursos@capitalcode.com.br"

## Criando repositório Local

Primeiramente, crie um repositório no seu explorador de arquivos e entre neste repositório com o git, o nome do nosso repositório e "Local":

    cd local
    git init

## Visualizando Status de nosso repositório

    git status

## Adicionando arquivos do Working Directory para a Staging Area

    git add local/
    or
    git add . 

## Adicionando arquivos da Staging Area para o Git Directory

    git commit -m "Meu Primeiro Commit"


 ## Alterando Mensagem de um Commit

    git rebase -i --root

## Saindo de Arquivo "VIM"

    :wq
    //Salva e sai do VIM

## Tags no Git

Tags são "apelidos" para índices no Git, dessa forma podemos transitar entre versões:

## Listar Tag

    git tag

## Criar Tag

    git tag -a v1.0 -m "Versão 1.0"

## Listando Todos os Commits Realizados

    git log --pretty=oneline

## Criando Tag em Commit Existente

    git tag -a v1.2 521747298a3790fde1710f3aa2d03b55020575aa -m "Versão 1.2"

## Acessando Tags de Versões Anteriores

    git checkout v1.0

## Como Deletar uma Tag

Volte para o Branch Master 

    git checkout master

Delete a Tag

    git tag -d v1.0

   ## Branch

Um branch no Git é simplesmente um leve ponteiro móvel que aponta para o commit. O nome do branch padrão no Git é master. Como você inicialmente fez commits, você tem um branch principal (`master branch`) que aponta para o último commit que você fez. Cada vez que você faz um commit ele avança automaticamente.

## Listando Branch

    git branch

## Criando Branch

    git branch teste

Acabamos de criar um ambiente de teste

   ## Alternando entre Branches

    git checkout teste

## Merge entre Branches

Volte para o Branch master

    git checkout master

Agora faça o Merge (Junção entre os novos arquivos na Branch de teste e a Branch Master)

    git merge teste

## Deletando Branch

    git branch -d teste

## Ambiente Gráfico do Git

    gitk
    
## Gerando Chave ssh para acesso direto ao Github com o Git

    ssh-keygen

## Git Push

    git push https://github.com/Capitalcode/Curso-Github-Projecao.git

## Clonando Repositório do Github para o Git

    git clone https://github.com/Capitalcode/Curso-Github-Projecao.git



 

