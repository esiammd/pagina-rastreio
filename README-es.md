<p align="center">
    <img alt="Página de Rastreio" title="#pagina-rastreio" src=".github/pagina-rastreio.jpg" width="75%" />
</p>

<h4 align="center">
  Localizador de Envios de Objetos de Correo por CPF
</h4>

<p align="center">
  <a href="#-idioma">Idioma</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologia">Tecnologia</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cloud-api-externa">API externa</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-proyecto">Proyecto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-usar">Cómo usar</a>
</p>

### :globe_with_meridians: Idioma

Seleccione el idioma: [Portugués] (), Español, [Inglés] ()


### 🚀 Tecnologia

Este proyecto fue desarrollado con las siguientes tecnologías:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)


### :cloud: API externa

Para el seguimiento de objetos por correo, se utilizó la siguiente API:

- [RastroJs](https://github.com/talesluna/rastrojs)


### 💻 Proyecto

El Localizador de Envios es una página para la localización de los objetos enviados por correo mediante el CPF (Registro de Personas Física) del destinatario en lugar del código de envío del objeto. Por lo tanto, con un solo dato, el CPF, es posible comprobar el status de envío de diferentes objetos del destinatario con una única búsqueda en la página.

Cabe mencionar que la página en cuestión fue diseñada para localizar el envío de productos de la Loja X (tienda ficticia) a sus clientes. Por este motivo, el sistema cuenta con su propia base de datos para registrar destinatarios y sus respectivos objetos de envío (productos comprados en la Loja X).

La base de datos se actualiza mediante el envío de un archivo CSV, por parte del administrador de la Loja X, a la Página de Seguimiento, que contiene algunos datos del destinatario y de los productos enviados a este por correo.


### 🤔 Cómo usar

- Descargue el repositorio en su máquina;

- Dentro de la carpeta 'page-tracking-backend':

  - cambie el nombre del documento '.env.example' a '.env'
  - configure las variables de entorno contenidas en el documento '.env'
  - ejecute el comando 'yarn' o 'npm install' en el terminal, para agregar la carpeta node_modules
  - ejecute el comando 'yarn dev' o 'npm run dev' en el terminal para ejecutar el servidor

- Dentro de la carpeta 'pagina-crawl-frontend':
  - ejecute el comando 'yarn' o 'npm install' en el terminal, para agregar la carpeta node_modules
  - ejecute el comando 'yarn dev' o 'npm run dev' en el terminal para ejecutar el frontend
