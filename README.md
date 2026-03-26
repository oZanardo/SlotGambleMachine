# SlotGambleMachine
Why this project? cuz with it I'll practice my programming logic, with the user depoist, their balance, make different scenarios with one line or multiple lines bet, we need to see if any of the lines got right, generate the items and get the prize and give back to them and be able to take off the money
# GIT

[https://www.youtube.com/watch?v=6Czd1Yetaac](https://www.youtube.com/watch?v=6Czd1Yetaac)

# Repositorios Git

[https://github.com/manoelcampos/sistema-bancario-java-junit](https://github.com/manoelcampos/sistema-bancario-java-junit)

[https://github.com/Jeconias/sistema-bancario](https://github.com/Jeconias/sistema-bancario)

## ReadMe

https://www.youtube.com/watch?v=k4Rsy8GbKE0

https://www.youtube.com/watch?v=TsaLQAetPLU

https://git-scm.com/cheat-sheet

### Video para recaptulação

https://www.youtube.com/watch?v=pyM5QLS2h6M&t=1370s

O git é um software de versionamento de código, o que significa que ele te ajuda a salvar versões do código para que se por um acaso você quiser voltar pra versão anterior do seu código isso é possivel

## Conceitos base de Git

A gente costuma no GIT ter uma branch(ramificação principal) que seria a versão que o app que o cliente irá utilizar, normalmente é chamada de main/master, e a partir dela nós criamos novas alterações para testar o código e novas funções, depois de testar as novas funções colocamos junto no código principal(merge/mescla o código), na branch main. 

O funcionamento do Git é que ele não salva todo o código anterior, mas sim a diferença de como estava o código antes e o que mudou pra agora

![image.png](GIT/image.png)

## Git Milestone

É a junção de várias Issues(Todo) para ajudar no tracking do que tem que ser feito no código, e conforme vamos concluindo as Issues a Milestone vai se atualizando e mostrando a porcentagem que falta para ser concluida

## Git commands

Comandos git

git init = Cria a pasta do git 

git status = mostra o status dos itens/códigos da pasta controlada

git add “(nome do arquivo)” = dessa maneira será adicionado cada arquivo individualmente

git add . = dessa outra maneira, usando o “.” o git adicionara todos os itens pendentes

git commit -m “(mensagem/ o que foi feito na versão)” = Esse comando cria a versão dos documento. Obs: na primeira versão utilizamos normalmente o nome “commit inicial” 

git commit --amend = usado para “remendar” o último commit, se esquecer de fazer uma pequena alteração

git diff = ele mostra as alterações da versão atual do programa e a que sofreu alteração

git fetch = syncroniza o historico de todas as alterações feitas no repositório

git log = historico das versões

gir restore <file> = descarta as alterações que foram feitas

git remote add origin (url do repositório) = esse comando serve para declarar onde vai estar localizado o repositório

git push <nome do repositorio remoto> (nome da branch) = esse comando é usado para enviar a versão para o git

git pull <nome do repositorio remoto> (nome da branch) = esse comando é usado para puxar a versão mais recente do (github) para seu desktop

git reflog = comando usado para ver o histórico de versões 

git rest (nome do arquivo) = ele é usado para voltar a versão antes de ser add ao git

git reset --hard (n**º** do id da versão desejada) = esse comando serve para voltar o código para a outra versão que vc quiser. Obs : você consegue o número do id no comando **reflog,** você consegue ver o número na frente da versão

## Comandos de branch

git branch = utilizado para ver todas as branchs criadas e quais estão disponiveis

git branch (nome da branch) = utilizado para criar um branch nova

git checkout (nome da branch) = utilizado para ir para outra branch

git checkout -b (nome da nova branch) = comando usado para criar uma branch e já mudar para ela. A segunda branch é uma branch já criada, e é qual vc vai usar como base para criar outra

## Comando merge

git merge (nome da branch) - o comando vai juntar as duas branchs. Obs : vai sub-escrever a branch atual pela que você pediu, antes de fundir as duas tenha certeza que está no código mais atualizado possivel. 

No sistema de merge tbm pode haver uma pessoa que vai analisar o código e conferir se ele está apto a fazer o merge, para enviar o pedido teremos que entrar na plataforma onde está o código(github) e mandar um pull request

## Repositório remoto

git remote add oriogin(nome do repositorio, o padrao é origin) <link> = para adicionar o repositório remoto

## Ignore

touch .gitignore = esse comando irá criar um documento no qual o git vai ignorar os documento que estão “dentro dele”. Obs : os arquivos você deve escrever o caminho no arquivo “gitignore”
