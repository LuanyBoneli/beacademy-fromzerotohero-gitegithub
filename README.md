# beacademy-devstart-gitegithub


# Comandos do Git

Comandos vistos nas aulas de git

## Comandos do Git

git config --global user.name configura usuário

git config --global user.email configura email de usuário

git status mostra o status do git

git init inicia repositório vazio

git add movimenta uma alteração de untracked para staged, pronta para o commit

git add . move todas as alterações de untracked para staged, prontas para o commit

git rm --cached remove uma alteração de staged para untracked

git commit -m registra a alteração por commit

git log mostra informações sobre os commits criados

git branch mostra as versões existentes

git branch  cria uma versão

git checkout navega entre versões

git checkout -b  cria uma versão e navega para ela

git branch -d  exclui uma versão

git merge unifica as versões

git clone "chave SSH" clona um repositório remoto para a sua máquina

git remote -v mostra repositório de origem

git push envia as alterações para o repositório remoto

git stash –include-untracked salva alterações sem commit

git stash pop restabelece alterações salvas

git stash pop stash executa stash especifico

git stash list lista stashes

git revert os 4 primeiros dígitos do hash do commit inverte as mudanças de um commit e gera um novo commit com o conteúdo alterado.
