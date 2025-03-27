git status usado para verificar quais arquivos foram alterados\criados e estão prontos para o commit

git add utilizado para adicionar arquivos para o controle do git

git commit estabelece a alteração dos arquivos na arvores 

git mv usado para mover um aquivo ou renomea-lo

git rm usado para remover arquivos

gitignore um arquivo contendo os arquivos e serão ignorados pelo git

git push usado para enviar o projeto modificado para o repositório

git pull usado para baixar o projeto do repositório

git checkout usado para recuperar o arquivo do diretorio cancelando modificações efetuadas. 
    Tambem usado para mudar as branchs:
        git checkout "nome da branch"; muda a branch
        git checkout -b "nome da branch"; cria e muda para nova branch com um unico comando

git branch usado para ver as branches do projeto ou criar uma nova branch
-d ou --delete exclui o branch 

git stash usado para criar um ponto de retorno e limpar as modificações efetuadas após a ultimo commit
git stash list usado para listar as stashs criadas
git stash apply usado para recuperar uma das stashs
git stash show -p 0 usado para ver o que foi alterado na stash passada
git stash drop 1 usado para removar uma stash da lista
git stash clear usado para remover todas as stashs

git tag -a "tag" -m "msg" usado para criar um ponto de retorno sem apagar o codigo, criando fases de desenvolvimento
git tag lista as tags criadas
git push origin <tag> enviar a tag especifica para o repositorio
git push origin --tags envia todas as tags para o repositorio

git show <tag> exibe as inforamações sobre a tag\versao ou ultimas atualizações\commit
git checkout <tag> também pode mudar para a tag
git diff <branch\arquivo> <branch\arquivo> usado para verificar as diferenças entre o branch atual e o repositorio remoto
git clean vai limpar arquivos não trackeados pelo git
git gc (garbage collector) é usado para que o git identifique arquvios que não são mais necessarios e excluia-os. Melhora performance.
git fsck (File System Check) verifica a integridade dos arquivos

git archive --format zip --output master_files.zip master 
    cria um arquivo comprimido do repositorio

git shortlog da um log resumido do projeto
git log da um log mostrando os commits de uma branch
git reflog vai mapear tudo que foi efetuado o repositorio.

git remote add origin "link" utilizado para adicionar um repositorio 
git remote rm origin utilizado para removar o repositorio

git submodule add <origin> usado para adicionar submodulos (dois ou mais projetos no mesmo repositorio)
git submodule usado para verificar os submodulos 
git push --recurse-submodules=on-demand usado para dar push em submodulos