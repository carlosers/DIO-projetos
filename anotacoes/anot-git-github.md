# comandos básicos

## git clone
use git clone para baixar um **novo** repositório do github para sua maquina local.

exemplo: git clone https://github.com/carlosers/DIO-projetos.git

## git status
use para saber qual e como está sua branch atual.

exemplo: git status

## git add
use para adicionar as alterações realizadas em seu repositório local, assim o git saberá que as alterações estão no estágio de pré-confirmação aguardando apenas o commit.

exemplo: git add <nome do arquivo ou pasta>
         git add .

### Para o primeiro exemplo será adcionado um arquivo ou pasta especifica listada pelo git status e no segundo exemplo serão adicionados todos de uma só vez.

# git commit
confirma as alterações na branch em que estiver trabalhando

exemplo: git commit -m "bla bla bla"

# Vale a pena rever
dica github para criar um repositório novo pela linha de comando (terminal).
echo "# meuProjeto" >> README.md
git init
git add README.md
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/carlosers/meuProjeto.git
git push -u origin main

…ou atualize um repositorio local com alterações que subiram via terminal
git remote add origin https://github.com/carlosers/meuProjeto.git
git branch -M main
git push -u origin main