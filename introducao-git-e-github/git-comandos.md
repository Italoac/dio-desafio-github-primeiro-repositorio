#Link para donwload do Git: https://git-scm.com/downloads
#O Git Bash é um terminal extendido para otimizar o uso do Gitm por meio de comandos gravados.

##Criar repositório local através do GIT BASH
1 - Comandos para criar arquivo no Git

	- Abra o terminal do GIT BASH

2 - Criar repositório
	Procure o local para criar um pasta
	Digite o camando mkdir "Digite o nome da repositório"
		Ex.: mkdir dio-my-projects

3 - Acesse a pasta criada
	cd "Nome da pasta"
		Ex.: cd dio-my-projects

4 - Comando iniciar o Git
	git init
		Se aparecer a mensagem Initialized empty Git, estamos no 		caminho certo.

5 - Comando mostrar arquivos dentro da pasta
	ls

6 - Mostra arquivos ocultos dentro da pasta
	ls -a

7 - Comando para voltar diretório anterior
	cd ..

8 - Comando para configuração inicial do seu email e nome no GIT
	git config --global user.email "Seu email" 
	git config --global user.name "Seu nome"

9 - 


##Copiar arquivos do GitHub para o Git

1 - No GitHub, acessar o repositório, clicar em code, aparecerá Local, clicar em HTTPS, copiar o link que está em HTTPS.

2 - Abrir o GIT BASH em seu computador, navegar até a pasta que queira salvar o arquivo, e digitar o seguinte comando no GitBash:
	git clone "HTTPS que copiou"
	Ex.:
	git clone https://github.com/Italoac/dio-desafio-github-primeiro-repositorio.git
	O repositório que você tem no GitHub será clonado para a pasta que escolheu através do Git.

3 - Para acessar o repositório com o arquivo dentro do GitBash, digite os seguintes comandos.
	cd "nome da pasta que criou o repositório"
	Ex.: cd dio-desafio-github-primeiro-repositorio/
	Agora você tem acesso ao Repositório com o arquivo Local

4 - Digite git status para verificar se está tudo certo. Se estiver certo aparece a segunite mensagem abaixo:
	On branch main
	Your branch is up to date with 'origin/main'.

#Fazer controle de versão do arquivo Git para enviar arquivos ao GitHub.

1 - No terminal Git Bash, dentro do repositório que estão os arquivos, digite o comando.
	git status (esse comando verifica se tem algum informação nova na pasta), se tiver novas informações aparece uma tela conforme abaixo:

	On branch main
	Your branch is up to date with 'origin/main'.
	Untracked files:
  	(use "git add <file>..." to include in what will be committed)
        introducao-git-e-github/

2 - Para enviar as informações da sua pasta local do Git para o  controle de versão local digite o seguinte comando.
	git add .


#Enviar arquivos do Git para o GitHub.
1 - Digite o comando abaixo
	git commit -m "Comentar sobre o que alterou no projeto"
	Ex.: git commit -m "Inclusão das anotações do curso de Git/GitHub"

2 - Comando de envio local do Git para o GitHub
	git push origin main



 

