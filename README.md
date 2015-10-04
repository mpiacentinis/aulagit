#Arquivo Criado para Demonstrar o Git 

##Comandos utilizados

mkdir aulagit

cd aulagit/

vi README.md

git init

git add README.md

git commit -m "Primeiro Commit"

git remote add origin https://github.com/mpiacentinis/aulagit.git

git push -u origin master

cat README.md 

vi README.md 

git status

git commit -a -m "Aterando README"

git push -u origin master

git checkout -b branch funcionabilidade1

git branch

git checkout -b funcionabilidade1

git branch

vi arquivo.txt

git status

git add arquivo.txt 

git commit -m "Add Arquivo 1 - master"

git status

git -b master

git checkout master

git status

vi arquivo2

git add arquivo2 

git commit -m "add arquivo2 on master"

git branch -a

git push origin master

git checkout funcionabilidades1

git checkout funcionabilidade1

git push origin funcionabilidade1

git log

git tag 0.1.0 

git push origin master --tags

gti tag -l




#Comandos github


##Adicionar repositorio remoto

git remote add origin https://github.com/mpiacentinis/aulagit.git ( aulagit.git = repositorio )

####Enviando arquivos para o remoto.

git push -u origin master

####Enviando arqjivos e um novo branch

git push origin novobrach 


####Listar os branch 

git branch -a

####Sincronizar  branch remotos

git pull

####Baixando / tendo acesso arquivos do brach remoto

git checkout -b nomebranch branchremoto


####Clonar um repositorio

git clone enderecorepositorio


####Criar um marcador - TAG ( gerar uma versao do sistema )

git tag 0.1.0 

####Subir uma tag para o remoto ( gerar uma versao do sistema )

git push origin master --tags

