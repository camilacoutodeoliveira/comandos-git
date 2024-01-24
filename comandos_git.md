# [Git e Github] Guia rápido e Comandos básicos

## Criando repositório local
git init
## Ver estado do Git
git status
## Adicionando seus arquivos ao Git
git add nome_do_arquivo
## Adicionar todos os arquivos
git add .
## Commit para que o Git possa rastrear suas modificações:
git commit -m 'seu comentário sobre seus arquivos aqui'
## Atualizando commit de arquivo modificado
git commit -am 'digite sua mensagem aqui'
## Ligando seu repositório local a sua nuvem
git remote add origin link_para_o_repositório_do_seu_projeto
## Enviando suas alterações. Pela primeira vez:
git push -u origin master
## Nas próximas vezes basta
git push
## Copiando um repositório
git clone link_para_o_repositório_que_deseja_copiar
## Criando branches
git checkout -b nome_do_branch
## Para voltar ao branch master ou branch especifico
git checkout master
git checkout nome_do_branch
## Seus branches locais não estarão na nuvem a menos que você os envie.
git push origin nome_do_branch
## Unindo branches
git merge nome_do_branch
## Atualizando seu repositório local. Pega as modificações que foram feitas no repositório remoto.
git pull
## Desfazendo commits
git revert chave_do_commit
## A chave do commit é encontrada através do comando:
git log