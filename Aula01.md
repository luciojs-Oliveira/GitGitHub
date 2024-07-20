fazer uma conta no github

email = 
senha = (colocar senha forte)

=================================================================================

Configuração no computador

1 - instalar o git no computador. Baixar o git com instalador (Standalone Installer)

2 - habilitar as variáveis de ambientes.

- iniciar

- editar variáveis de ambientes.

- variáveis de ambientes.

- variaveis do sistema.

- path

- editar

- adicionar a variável; exe : C:programas\Git\cmd


3 - configurar a cominicação git com o github

git config --global user.email "you@example.com"
git config --global user.email "luciojs.oliveira@gmail.com"

git config --global user.name "Your Name"
git config --global user.name "luciojs-Oliveira"













=================================================================================

Create a new repository = Criar novo repositório.


Repository name* = Nome do repositório.

Description (optional) = Descrição


Public or Private = a sua escolha.


Create repository = Cria um novo repositório.





=================================================================================


Atenção = Caso já não tenha um repositório local use esse comando para fazer um repositório local.
===============================================

…or create a new repository on the command line
echo "# GitGitHub" >> README.md
git init --------------------------------------------------------------------------- inicializa um projeto
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/luciojs-Oliveira/GitGitHub.git
git push -u origin main

Atenção = Caso já tenha um repositório local.
============================================

…or push an existing repository from the command line
git remote add origin https://github.com/luciojs-Oliveira/GitGitHub.git
git branch -M main
git push -u origin main



======================================================================================

comandos 

git --version --------------------------------- Exibe a versão do git 

git add . ------------------------------------- Adiciona todos os arquivos

git commit -m "mensagem do commit" ------------ Adiciona uma mensagem ao commmit


