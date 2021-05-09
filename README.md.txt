Sobre o Git : 
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

 - git init (Inicia o git dentro da pasta selecionada).
 - git status (para verificar o status da sua pasta).
 - git add -a (para adicionar todos os arquivos criados na pasta do projeto).
 - git add + nome do arquivo (para adicionar apenas um arquivo que foi criado dentro da pasta do projeto).
 - git commit -m "Comentário aqui" (para adicionar um comentário ou alteração feita dentro do projeto).
 - git commit -am "comentário aqui" (para adicionar um comentário sem passar pelo "git add", ou seja, vai ser adicionado automaticamente sem precisar fazer o add na mão).
 - git log (para ver todos os commit's adicionados ,quem fez e a data da adição ou alteração no código).
 - git reset (serve para voltar em algum commit específico), este da para usar de 3 jeitos:
git reset -soft (vai mostrar as alterações que foram feitas,porém sem os commit's. Ou seja, vaii voltar para um estado antes de ter sido reaizado o commit, pronto para ser
commitado novamente)este é o mais recomendado para usar por uma equipe de desenvolvimento.
git reset -mixed (o mesmo do soft porém sem a chance de dar um novo commit).
git reset -hard (vai mostrar somente o primeiro commit, tudo o que tiver em outro estado vai ser desconsiderado do contexto) este não é recomendado para ser usado dentro 
de uma equipe de desenvolvimento.
 - git branch (para ver todas as branch's que há dentro da pasta do projeto).
 - git checkout + nome da branch (vai alterar a branch que está sendo usada).
 - git checkout HEAD --nome do projeto (vai voltar o projeto escolhido para o estado original).

Comandos dentro do Git:
 - git init (Inicia o git dentro da pasta selecionada).
 - git remote add origin https://github.com/voce/suapasta.git (esses comandos estão no GutHub).
 - git branch -M + branch do projeto (adiciona a sua branch ao GIT)
 - git push -u origin branch do projeto (Adiciona esta branch ao seu GitHub, onde push significa que você vai levar uma informação sua para outro local,no caso GitHub).
 

