<p align="center">
    <img alt="Página de Rastreio" title="#pagina-rastreio" src=".github/pagina-rastreio.jpg" width="75%" />
</p>

<h4 align="center">
  Página de Rastreio de Objetos do Correio por CPF
</h4>

<p align="center">
  <a href="#-idioma">Idioma</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologia">Tecnologia</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cloud-api-externa">API externa</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-usar">Como usar</a>
</p>

### :globe_with_meridians: Idioma

Selecione o idioma: Português, [Espanhol](), [Inglês]()


### 🚀 Tecnologia

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)


### :cloud: API externa

Para realização do rastreio dos objetos pelo correio utilizou-se a seguinte API:

- [RastroJs](https://github.com/talesluna/rastrojs)


### 💻 Projeto

A Página de Rastreio é uma página para rastreio de objetos enviados por correio, a qual utiliza o CPF do destinatário em lugar do código de rastreio do objeto. Sendo assim, com um único dado, o CPF, é possível verificar o status de envio de diferentes objetos do destinatário com uma única busca na página.

Vale resaltar que a página em questão foi pensada para o rastreio do envio de produtos da Loja X (loja fictícia) para seus clientes. Por essa razão, o sistema possui um banco de dados próprio para cadastro dos destinatários e seus respectivos objetos de rastreio (produtos comprados na Loja X).

O banco de dados é atualizado mediante o envio de um arquivo CSV, pelo administrador da Loja X, a Página de Rastreio, contendo alguns dados do destinatário e dos produtos enviados por correio ao mesmo.


### 🤔 Como usar

- Baixe o repositório em sua máquina;

- Dentro da pasta 'pagina-rastreio-backend':

  - renomeie o documento '.env.example' para '.env'
  - configure as variáveis de ambiente contidas no documento '.env'
  - execute no terminal o comando 'yarn' ou 'npm install', para adicionar a pasta node_modules 
  - execute no terminal o comando 'yarn dev' ou 'npm run dev' para executar o servidor

- Dentro da pasta 'pagina-rastreio-frontend':
  - execute no terminal o comando 'yarn' ou 'npm install', para adicionar a pasta node_modules
  - execute no terminal o comando 'yarn start' ou 'npm run start' para executar a front-end
