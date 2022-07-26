Olá, essas são algumas anotações sobre como utilizar o git!

--Git --version
Git --version: apresenta a versão do git que está instalada.

--Git init
Git init: faz com que o git inicialize um repositório no diretório em que o comando foi executado.

--Git add 'nome do projeto'
Git add: faz comn que o git adicione seu projeto dentro da branch, deixando ele na espera para ser commitado.

--Git add .
Git add .: faz com que todas as alterações feitas sejam colocadas na area de espera diferente de quando definimos um projeto especifico.

--Git commit -m "Mensagem"
Git Commit -m: faz o comit dos projetos adicionados no git add.

--Git branch -m "nome"
Git branch -m: permite que o nome da branch principal geralmente chamada de master seja alterada.

--Git remote add origin "link do repositório" (shift+insert) (insert) (ctrl+shift+v)
Git remote add origin: faz com que o git conecte o repositório local ao repositório do GitHub chamado de Origin.

--Git push -u origin main (main ou o nome da branch em que estamos)
Git push -u origin main: faz com que o git empurre os commits feitos no repositório local para o repositório do GitHub.

--Git push origin(nome da branch)
Git push: Diferente do comando antrerior, após feita a primeira conexão não precisamos utilizar mais o -u origin, e sim push nome da branch.

--Git checkout -b "nome"
Git checkout -b "nome": cria uma nova branch e muda o local em que estamos desenvolvendo, saindo da main para a nova.

--Git merge (nome da branch)
Git merge: faz com que as alterações feitas na branch mencionada se mesclem com a branch principal, sincronizando as duas.

--Git clone "link do repositório" (shift+insert) (insert) (ctrl+shift+v)
Git clone: clona um repositório existente para a nossa maquina.

--clear
Clear: faz uma limpeza no terminal em que estamos utilizando.