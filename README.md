# Mongodb
Introdução a banco de dados (Mongodb)


MongoDB é um banco de dados não relacional (noSQL) que armazena e consulta dados do tipo JSON. 

### Instalação e inicialização

1. Fazer o download do [Mongodb](https://www.mongodb.com/try/download/community) e realizar a instalação;
2. Criar a pasta `C:\data\db`;
3. Abrir o prompt de comando e entrar a pasta do banco de dados `cd C:\Program Files\MongoDB\Server\3.2\bin>`;
4. Digitar o comando `mongod` e o servidor começará a rodar na porta 27017;
5. Abrir um novo prompt de comando, entrar na pasta `cd C:\Program Files\MongoDB\Server\3.2\bin>` e depois digitar `mongo`;
6. Fazer o download do [Robo 3t](https://robomongo.org/download);
7. Abrir o Robo 3t e criar uma nova conexão em `localhost:27017`.


### Usando Robo 3t

Clicar com o lado direito em cima do Collections e "Criar uma nova connection".

##### Visualiza o que contém na Collections

`db.getCollection('NOME').find({})`

##### Adicionar documento na Collections

Clica com o lado direito em cima da pasta Collections e cria uma nova

##### Consultar documento

`db.nomedacollection.find({selecao})`

##### Atualizar documento

Clica com o lado direito no documento e escolher update document. <br>
ou `db.nomedacollection.update({selecao}, {$set:{campos-atualizados}})`

##### Excluir documento

Clica com o lado direito no documento e escolher delete document. <br>
ou `db.Consultas.remove({selecao})`

##### Limitar documento

`db.nomedacollection.find().limit(numero)`

##### Pular documento

`db.nomedacollection.find().skip(numero)`

##### Ordenar documento

`db.nomedacollection.find().sort({<key>:1})`




