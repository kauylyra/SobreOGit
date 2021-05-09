O que é o Git?
O Git é um gerenciador de versionamento deum projeto, ele possibilita o usuário de voltar o tempo dentro de código, ou seja, se você quiser voltar o código para ver como
estava o código antes da alteração, ou se achou que a alteração não está de acordo com o padrão que foi previsto e quiser voltar para o código original, com o Git você 
pode fazer isso.

O que é Readme?
 - Readme = leia-me. Sempre que criado um projeto que vai subir para o GitHub deve-se criar um arquivo de texto chamado README.md, é aonde vai ter a descrição/explicação
do seu projeto.

O que é Commit?
 - Commit são comentários que ocorre após uma alteração no Projeto ou inclusão de um outro arquivo realizado por alguém da equipe, ou seja, se algum menbro da equipe 
fizer uma alteração
no código ou incluiu algo dentro do projeto desenvolvido coloca-se um comentário sobre o que ele fez, Exemplo:
"Alteração na linha 23 e inclusão de um arquivo Index.html no projeto".
Isso facilita o entendimento dos colaboradores da equipe que realizou essa alteração, pois no Commit é incluído a data,hora e qual Usuário fez aquela alteração/inclusão.

O que é Branch's?
 - Branch's são as versões diferentes dentro de um sistema, pois dentro de uma equipe pode-se trabalhar em diferentes versionamentos.Por exemplo se um membro da sua equipe
for de outro país e as versões entre eles são diferentes, consegue-se fazer alterações nos códigos de acordo com cada versão. A versão vai ser denominada a partir da data 
qur foi criado um novo Branch.Após o Primeiro Commit dado dentro do seu código cria-se automaticamente uma versão do sistema (Branch) chamada de "Master".A Master é a 
primeira versão que foi criada naquele projeto.

Comandos dentro do Prompt de comando.
 Os comandos mais utilizados no prompt são:

 - git init (inicia o git dentro da pasta selecionada).

 - git status (para verificar o status da sua pasta).

 - git add -a (para adicionar todos os arquivos criados na pasta do projeto).

 - git add + nome do arquivo (para adicionar apenas um arquivo que foi criado dentro da pasta do projeto).

 - git commit -m "Comentário aqui" (para adicionar um comentário ou alteração feita dentro do projeto).

 - git commit -am "comentário aqui" (para adicionar um comentário sem passar pelo "git add", ou seja, vai ser adicionado automaticamente sem precisar fazer o add na mão).

 - git log (para ver todos os commit's adicionados ,quem fez e a data da adição ou alteração no código).

 - git reset (serve para voltar em algum commit específico), este da para usar de 3 jeitos:

 - git reset -soft (vai mostrar as alterações que foram feitas,porém sem os commit's. Ou seja, vaii voltar para um estado antes de ter sido reaizado o commit, pronto para ser
commitado novamente)este é o mais recomendado para usar por uma equipe de desenvolvimento.

 - git reset -mixed (o mesmo do soft porém sem a chance de dar um novo commit).

 - git reset -hard (Vai mostrar somente o primeiro commit, tudo o que tiver em outro estado vai ser desconsiderado do contexto) este não é recomendado para ser usado dentro 
de uma equipe de desenvolvimento.

 - git branch (para ver todas as branch's que há dentro da pasta do projeto).

 - git checkout + nome da branch (vai alterar a branch que está sendo usada).

 - git checkout HEAD --nome do projeto (vai voltar o projeto escolhido para o estado original).

Comandos dentro do Git:

 - git init (inicia o git dentro da pasta selecionada).

 - git remote add origin https://github.com/voce/suapasta.git (esses comandos estão no GutHub).

 - git branch -M + branch do projeto (adiciona a sua branch ao GIT).

 - git pull origin +branch (vai puxar os arquivos ou projetos do repositório para a sua máquina local):
 **Uma boa prática é fazer o pull antes de fazer o push, pois assim você sempre mantém o repositório atualizado, tanto com seus arquivos quanto com o que foi mandado de outros
membros de sua equipe.**

 - git push -u origin branch do projeto (adiciona esta branch ao seu GitHub, "push" significa que você vai levar uma informação sua para outro local. No casopara o  GitHub).

 - git push origin : + branch do projeto ou arquivo (remove do repositório a branch ou arquivo escolhido).

 - git branch -D + nome do branch (remove o branch da sua máquina local).

 - git ignore (ignora alguns arquivos que não é relevante ficar no repositório).

 - git revert--no-edit (retorna o código para o estado anterior porém sem perder o que foi alterado, linhas que você adicionou ou alterou vão ser desfeitas, más nao perdidas).
 

