# Guia Definitivo Git e GitHub

## Iniciando um Repositório

- 1° Passo - Instalar o Git no Computador (Software de versionamento Local)

- 2° Passo - Configurar o Software de Versionamento
           - git config --global user.name "UserName" 
           - git config --global user.email "email" 
           - git --version
           - git config --list

- 3° Passo - Iniciar o repositório Local
           - git init (criar o ambiente de versionamento na pasta do projeto)             

- 4° Passo - Iniciar o repositório Online (GitHub) 
           -  Entrar no GitHub    
           - conectar o Git ao GitHub
           - git remote add origin https://github.com/ju130-star/GuiaDef_GitGitHub.git 
           - git remote get-url origin -> retorna o link  
           - git remote set-url origin +link_do_repositorio-> Alterar o link.

- 5° Passo - Adicionar meus arquivos ao repositório local
           - git add+nome_do_arquivo -> Adiciona um por um
           - git add . -> Adiciona todos os arquivos de uma única vez.
                        