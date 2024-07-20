fazer uma conta no github

email = 
senha = (colocar senha forte)

==================================================================================

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


3 - configurar a cominicação do git com o github

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


Atenção = Caso não tenha um repositório local use esse comando para fazer um repositório local.

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

git --version ------------------------------------------------------------------ Exibe a versão do git 

git add . ---------------------------------------------------------------------- Adiciona todos os arquivos

git commit -m "mensagem do commit" --------------------------------------------- Adiciona uma mensagem ao commmit

Atenção = trocar protocolo Http para SSH 
========================================

git remote add origin git@github.com:luciojs-Oliveira/GitGitHub.git ------------- Conecta repositório local ao git hub.


git push -u origin main --------------------------------------------------------- Envia os arquivos para o github.


======================================================================================

gerando chave ssh pelo terminal

comando : ssh-keygen -t ed25519 -C "luciojs.oliveira@gmail.com"

Após gerar a chave, ela estará na pasta 'ssh'.
colar está chave no git hub = Add new SSH Key.

======================================================================================

Para excluir um repositório no github: Danger Zone

- Entrar no repositório que deseja excluir.

- Settings

- Descer até o final da página.

- Escolher a opção: Delete this repository.

Isso excluirá permanentemente o repositório luciojs-Oliveira/GitGitHub, wiki, problemas, comentários, pacotes, segredos, execuções de fluxo de trabalho e removerá todas as associações de colaboradores.
This will permanently delete the luciojs-Oliveira/GitGitHub repository, wiki, issues, comments, packages, secrets, workflow runs, and remove all collaborator associations.


Quero excluir este repositório
I want to delete this repository


Eu li e compreendi esses efeitos
I have read and understand these affects

Para confirmar, digite "luciojs-Oliveira/GitGitHub" na caixa abaixo
To confirm, type "luciojs-Oliveira/GitGitHub" in the box below