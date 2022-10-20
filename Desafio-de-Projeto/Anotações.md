## Introdução ao Git/GitHub :man_technologist:

### Comandos

Cada um desses comandos representa uma movimentação dentro do Git Bash

dir 

cd /

cd ..

cls 

tab

echo

del

rmdir

mv

ls

cat

pwd

### Como criar uma chave SSH e validar no GIT

Utilizar o seguinte código no Git Bash

ssh-keygen -t ed 25519 -c email GitHub 

Desse modo ir até o GitHub seguindo os passos

Settings >>> SSH and GPG Keys >>> New SSH Key >>> Acrescentar novo Title >>> Colar a chave criada no GitBash 

### Iniciando o Git

#### Comandos

Git Init

Git Add

Git Commit

Realizar uma configuração Inicial com o seguinte comando:

git config --global user.email "email do GitHub"

git config --global user.name "name do GitHub"

Existe outra forma de colocar ao invés de "--global" sendo algo local, mas não foi ensinado. **Procurar informação sobre esse detalhe**

#### Comitando o Arquivo 

git add *  ou git add .

git commit -m "descrever o que está sendo realizado com clareza"

#### Verificando o Status

git status 

#### Como fazer alteração do nome e email 

Utilizar o seguinte código 

git config --list  (Para verificar)

git config --global --unset 

### Apontando o Repositório

Primeiramente adicionar a 1ª origem com o seguinte código 

git remote add origin (colocar o link do repositório)  **A palavra origin é por convenção, porém, poderia colocar qualquer nome**

git remote -v

git push origin (master ou outro nome que esteja locado)
