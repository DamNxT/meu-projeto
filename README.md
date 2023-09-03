# meu-projeto
Estou usando este repositório para aprender sobre git.

git init
-iniciar um novo projeto com git

git add <nome-arquivo> ou .
-adiciona os arquivos que estão prontos para serem commits

git commit -m "mensagem de commit"
-commit os arquivos no histórico

git log
-mostra os últimos commit, log de alterações

git status
-mostra o estado da ramificação

git diff
-mostra o que foi alterado
-o que tem de alteração na ramificação atual

git merge
-merge de ramificações, mescla ramificações

git branch
-mostra a branch atual

git branch -b <nome-da-branch>
-cria uma nova branch a partir da branch atual que estamos

git checkout <nome-da-branch>
-muda para essa branch 

git remote add <nome> <URL>
-adiciona um novo repositório remoto

git push <nome> <nome-da-branch>
-manda as alterações locais para o repositório remoto, para cada branch

git pull <nome> <nome-da-branch>
-pega as alterações do repositório remoto e joga para a máquina

git fetch
-atualiza o repositório local de acordo com o histórico salvo no repositório remoto
-sincronização do local com o remoto