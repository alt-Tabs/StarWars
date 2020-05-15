# Star Wars

![darth](https://user-images.githubusercontent.com/53315899/81985694-f99fe100-960c-11ea-9808-77c22dd6c939.png)

Este repositório serve de exemplo para o curso de Git e Github.

## Lista de comandos básicos:

**git checkout** -  Alternar entre branchs, alternar entre commits.

**git push** - Coloca suas alterações(commits) locais em seu repositório remoto.

**git pull** - Traz as alterações(commits) de seu repositório remoto para seu repositório(branch) local.

**git branch < nome_da_branch >** - Cria uma nova branch à partir da que você está, use "git checkout nome_da_branch" para ir para a branch criada.

**git branch -d < nome_da_branch >** - Deleta a branch "nome_da_branch" de seu repositório local.

**git revert < algum_commit >** -  Vai criar um commit para desfazer as alterações feitas ao criar "algum_commit", é útil para desfazer um commit antigo.

**git reset < commit >** - Reseta o repositório local para um determinado commit

**git reset --hard < commit >** - Reseta e remove todas as alterações. *Cuidado ao usar! Não use se já estiver publicado esse commit em seu repositório remoto*