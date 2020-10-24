<p align="center">
    <img alt="Página de Rastreio" title="#pagina-rastreio" src=".github/pagina-rastreio.jpg" width="75%" />
</p>

<h4 align="center">
  CPF Mail Objects Tracking Page
</h4>

<p align="center">
  <a href="#-language">Language</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technology">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cloud-api-externa">API externa</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How to use</a>
</p>

### :globe_with_meridians: Language

Select the language: [Portuguese] (), [Spanish] (), English

### 🚀 Technology

This project was developed with the following technologies:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)


### :cloud: API externa

For tracking objects by mail, the following API was used:

- [RastroJs](https://github.com/talesluna/rastrojs)


### 💻 Project

The Tracking Page is a page for tracking objects sent by mail, which uses the recipient's CPF (Registration of Individuals) instead of the object's tracking code. Therefore, with a single data, the CPF, it is possible to check the status of sending different objects of the recipient with a single search on the page.

It is worth mentioning that the page in question was designed to track the sending of products from Loja X (fictional store) to its clients. For this reason, the system has its own database for registering recipients and their respective tracking objects (products bought at Store X).

The database is updated by sending a CSV file, by the Store X administrator, the Tracking Page, containing some data of the recipient and the products sent by mail to him.


### 🤔 How to use

- Download the repository on your machine;

- Inside the 'chat-pubsub-server' folder:

  - rename the document '.env.example' to '.env'
  - configure the environment variable contained ih the '.env' document
  - run the command 'yarn' or 'npm install', to add the node_modules folder
  - 'yarn knex: migrate' or 'npm run knex: migrate' to create the database tables
  - run the command 'yarn knex: seed' or 'npm run knex: seed' to fill the channel table (corresponding to the abstract authorization levels)
  - 'yarn dev' or 'npm run dev' to run the server

- Inside the 'chat-pubsub-frontend' folder:
  - run the command 'yarn' or 'npm install', to add the node_modules folder
  - run the command 'yarn start' or 'npm run start' to run the frontend

