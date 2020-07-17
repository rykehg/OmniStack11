
# OmniStack11

> Projeto simples de CRUD usando NodeJs React e React Native com o Expo

> #Node.Js #React #CRUD #ReactNative #SQLite 

## Instalação

## 1. Clone o repositório
> utilizando git clone `https://github.com/rykehg/OmniStack11` ou faça o download do repositório.

## 2. Para quem já conhece nodeJs e seus requisitos
> Pré-Requisitos do Projeto
> git, NodeJs, express, sqlite, knex, react, react-native, expo

- Para iniciar o Backend do React utilize os comandos:
```shell
$ cd backend
$ npm install ou yarn install
$ npm start ou yarn start
```

- Para iniciar o Frontend do React utilize os comandos:
```shell
$ cd frontend
$ npm install ou yarn install
$ npm start ou yarn start
```
> Assim que o processo terminar, automaticamente será aberta no seu navegador a página localhost:3000 contendo o Projeto.

### Para o mobile:
- Para testar o Mobile do React Native, primeiro coloque o endereço do seu servidor (ou computador) no arquivo src/services/api.js, e depois execute os comandos:

- NÃO é preciso executar a linha de baixo caso ja tenha o Expo (CLI) instalado!
```shell
$ yarn global add install expo-cli
```
- Excute no terminal os seguintes comandos:
```shell
$ cd mobile
$ yarn install
$ expo start
```
> Assim que o processo terminar, automaticamente será aberta no seu navegador a página localhost:19002. Conecte seu emulador, ou teste o aplicativo por LAN: baixe o aplicativo Expo da Play Store ou App Store e em seguida escaneie o código QR. (Se não for por lan, tente por tunnel, espere aparecer no Metro Blunder(informações do Expo sobre o app) a mensagem Tunnel Ready então clique em tunnel e escaneie o código QR.

## 2. Para quem é novo no universo NodeJs
### Para modificar e desenvolver a aplicação
### Instalando o NodeJs
> Node.js® é um runtime JavaScript desenvolvido com o Chrome's V8 JavaScript engine. Ou seja um navegador que roda no servidor backend. E junto com ele o seu proprio gerenciador de pacotes o "npm".
- Procure a opção "Outros Downloads" no site https://nodejs.org/pt-br/
- Nela vá até a opção "Instale Node.js usando gerenciador de pacotes." Use o recomendado para o seu sistema operacional.
- Para WIN10 o recomendado é o  Chocolatey, para isso siga a instruções do site deles: https://chocolatey.org/install.
- Executando o PowerShell como ADMINISTRADOR
- Execute o comando "choco" no PowerShell para verificar se funcionou (reinicie o terminal se for preciso)
- Depois execute o comando de instalação do node expecificando a versão LTS mostrada na página inicial do site do NODE
(para win10 "cisnt nodejs-lts")
- execute os comandos "node -v" e "npm -v" para checar se ocorreu tudo bem.
> Caso vc queira iniciar um projeto novo, navegue até a pasta do seu projeto backend e digite "npm init -y"

- Intale o Visual Studio Code da forma que preferir. 
Para deixa-lo mais amigavel ao JavaScript e NodeJs podemos instalar as extenções Dracula e Material Icon Theme

- Caso queira rodar o projeto em seu pc. Com todos as dependencias e ferramentas acima instaladas ir com o console (pode ser dentro do terminal do VS code) dentro da pasta "backend" e executar "npm install" para instalar todas as dependencias que faltam e que já estrão configuradas dentro do projeto. Depois com o console ainda dentro da pasta backend executar "npm start", para dar inicio ao projeto. Caso queira finalizalo precionar no console/terminal "Ctrl+C". 

- Para testar utilizar o software Insomnia (https://insomnia.rest). Importe o arquivo "Insomnia_2020-04-02.json" e é só executar os metodos POST e GET após iniciar o backend.

**Pacotes usados no BackEnd**
- Configaraçôes e documentação
"npm install express" - configurações de rotas - https://expressjs.com 

"npm install nodemon -D" - para reiniciar o servidor assim que um arquivo do node é salvo. O "-D" salva ele como uma ferramenta de desenvolvedor - https://github.com/remy/nodemon#nodemon

"npm install knex" - query builder para sqlite, mssql, postgres... - http://knexjs.org
"npm install sqlite3" - para fazer a conecção com com banco usando o knex" - http://knexjs.org
"npx knex init" - para iniciar um novo projeto com o knex o knexfile.js terá as informações de configuração do banco para a aplicação
"npx knex migrate:make create_NomeDaTabela" - arquivo que controla a criação de tabelas no banco
"npx knex migrate:latest" - executa a criação das tabelas configuradas nos arquivos criados pelo knex (Exemplos na pasta "src\database\migrations")

"npm install cors" - especifica as URLs que podem acessar a aplicação - https://www.npmjs.com/package/cors

OBS: Para debugar e saber como está a resposta sempre use o "console.log()"
---
### FrontEnd React
- Caso vc queira dar inicio a um novo projeto de front com React podemos executar no local que queremos criar a pasta do projeto "npx create-react-app frontend" (sendo que o nome da pasta criada será "frontend"). Para iniciar o modelo de front já incluso é só executar "npm start"

Lembrando que o React usa os conceitos de JSX e live-reload portanto a cada modificação de arquivo as mudanças podem ser visualizadas na hora.

- Para instalar todas as dependencias do projeto executar na pasta frontend o comando "npm install"

**Pacotes usados no FrontEnd**
```shell $ npm install react-icons``` - pacote com icones variados usado na aplicação - https://react-icons.netlify.com
```shell npm install react-router-dom``` - pacote de configurações de rotas do react - https://www.npmjs.com/package/react-router-dom
---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
