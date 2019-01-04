======== Comandos uteis do git ================

//este comando atribui o nome do usuario no repositorio 
git config --global user.name "fulano de tal"

//este comando atribui o email do usuraio no repositorio
git config --global user.name "fulanodetal@gmail.com"

//este comando cria um repositorio no diretorio
git init

//verifica se tem novos arquivos criados ou alterados no repositorio
git status

//adiciona os arquivos criados/auterados no repositorio para serem commitados
possuindo 3 variações
ex:
// adiciona somente o arquivo selecionado
git add index.html
// adiciona todos os arquivos que possuem determinada extenção
git add *.html
// adiciona tudo que estiver no repositorio sem distinção
git add .

----------------------------------------------------------------

// commita (grava os arquivos) permanentemente no repositorio é necessário tambem adicionar
uma mensagem com o -m
git commit -m "primeiro commit"

// atalho para adicionar e commitar ao mesmo tempo (!só funciona para arquivos previamentes adiconados)
git commit -am "commitando com atalho"

// informa o que foi adicionado ou removido no arquivo
git giff

// informa o que está pendente para o commit
git giff --staged

// mostra um historico de comites que foram feitos no repositorio
git log

// mostra o historico dos comites mais o diff de cada arquivo commitado
git log -p

// mostra a quantidade de commites feita mostrando o commit mais atual
git log -p -1

// mostra um relatorio de forma detalhada em uma interface grafica
gitk

// mostra apenas os códigos (enderços) dos commits
git log --pretty=oneline 

//edidanto o commit
git --amend -m " "

//remove os arquivos adicionados ao repositorio para serem commitados
git reset HEAD nomedoarquivo.txt

//descarta as mudanças feitas no seu arquivo adiionado no repositorio
git checkout -- nomedoarquivo.txt

//quando o arquivo e removido do diretorio local ele tambem precisa ser removido do git
git rm nomedoarquivo.txt

