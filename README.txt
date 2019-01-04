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

// atalho para adicionar e commitar ao mesmo tempo
git commit -am "commitando com atalho"

git deff



