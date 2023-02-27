# Simple WebServer com Node.js

Olá a todos, este é mais um pequeno projeto criado para fins de estudo e aprimoramento nos meus conceitos de backend para Web. O intuito aqui é criar um pequeno servidor web usando node.js e javascript. Também estou usando um módulo do node chamado _nodemon_ para auxiliar no desenvolvimento do servidor. 

## Principais tecnologias utilizadas

* _JavaScript_ como linguagem de programação
* _Node.js_
* _nodemon_

## Estrutura do projeto

O projeto conta com a seguinte estrutura:

* _static/_: diretório onde estão os arquivos que serão manipulados pelo servidor e retornados ao cliente
* _config.json_: arquivo de configurações do servidor
* _package.json_: arquivo de configuração do projeto, criado com o comando `npm init`
* _index.js_: Arquivo principal do projeto. É ele que será executado quando usarmos o comando `nodemon index.js`
* _server.js_: Implementação do servidor.
* _filehandler.js_: Módulo para manipulação dos arquivos do servidor.

