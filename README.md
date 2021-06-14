#Resumo do fluxo e de todas as branchs.

## Main
Ao criar o repositório, foi gerado a branch master.

Então foi renomeado a branch master
com o seguinte comando: 


git branch -m master main

Primeiro parametro (nome da branch atual) e segundo (novo nome da branch);

Então foi criado o arquivo1.js e arquivo2.js

então foi dado git status para verificar o que foi alterado ou criado;

git commit -m "primeiro commit" para gerar o commit.

git push para subir as alterações ao github.

Em seguida foi criado o arquivo3.js e gerado o commit dois.

E então criado as tags.
Com o comando
git tag -a 1.0 -m “versão de início”.

git push origin main --tags

Para subir as tags ao github.

em seguida 
Criada uma nova branch chamada dev a partir de main.
Utilizado o comando "git checkout dev" para alternar para a branch dev.



## DEV

Na branch dev foi deletado o arquivo2.js e criado o arquivo4.js
após isso criado o commit três.


 Adicionado uma linha no arquivo1.js e então Commit quatro.


Criado a branch temp a partir desta branch dev.

git checkout temp - para alternar a branch temp.


## TEMP

Na branch temp foi adicionado uma linha nos arquivos (arquivo3.js, arquivo4.js. Criado o arquivo5.js e adicionado uma linha)

Criado o commit cinco

git push 

Alterado para a branch dev com 'git checkout dev' e então feito um merge das branches temp e dev com o comando:

git merge --no-ff temp.


## DEV
Após merge com as branches dev e temp, foi deletado o arquivo 4 da branch dev e alterado uma linha no arquivo1.js.

Foi gerado um merge entre as branches DEV e MAIN.

## main

na branch main foi dado o comando git merge --no-ff dev. Para pegar as alterações mais recentes de DEV

em seguida para finalizar o projeto, dado o comando git git tag -a 1.1

e gerado um push das tags para finalizar o projeto.


## Versão final

 Gerado Merge entre Main e Dev