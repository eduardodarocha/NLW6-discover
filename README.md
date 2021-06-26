# \<nlw/\>together - [Rocketseat](https://rocketseat.com.br/)

## Trilha Discover

- Educadora Rocketseat: Jakelyne Gracielly

<h1 align="center">
  <img alt="Rocket.Q" title="Rocket.Q" src=".github/rocketq.png" width="220px" />
</h1>
<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-material">Material</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-aplicação">Aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8F-guia-de-estudos-e-organiza%C3%A7%C3%A3o">Guia de estudos e organização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="Rocket.Q" src=".github/Rocket_Q.png" width="90%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- HTML
- CSS
- JavaScript
- NodeJS
- EJS
- Express
- SQLite
- Beekeeper

## 💻 Projeto

O Rocket.Q é uma aplicação de interação através de perguntas, sendo possível criar uma sala para internautas anônimos fazerem perguntas e o criador da sala em posse de uma senha gerenciar essas perguntas e marcar como lidas.

## 🔖 Layout

Você pode visualizar o layout do projeto através [desse link](https://www.figma.com/file/vw2MQCdI7lVKzLP9y2F7ji/Roquet.q). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

## 📓 Material

Material para as aulas e configuração do ambiente no [Notion](https://www.notion.so/NLW6-Trilha-Discovery-3b4aa6b99e5741b6be1279b31100237c)

## Aplicação
### Como clonar e rodar a aplicação de modo local

Criar um diretório e entrar nele:
- `Clonar: git clone https://github.com/eduardodarocha/nlw-06-discover.git`
- Apagar o diretório "node_module" (baixei no github para fazer o deploy no git pages  ) e os arquivos "package.json" e "package-lock.json" que serão recriados posteriormente.
- Inicializar o projeto:
  - `npm init -y`
- Instalar as dependências:
  - `npm install express`
  - `npm install ejs`
  - `npm instal sqlite`
  - `npm instal sqlite3`
- Modificar o package.json: 
  - "main": "src/server.js",
  - `"scripts": {
    "start": "node src/server.js",
    "init-db": "node src/db/init.js"
  },`
- Inicializar o banco de dados:
    - `npm run init-db`
- Rodar a aplicação:
  - `npm start`
- Abrir o browser com endereço:
  <localhost:3000> ou <127.0.0.1:3000>


## 🗂️ Guia de estudos e organização

- Aprendizado ativo x passivo
  - Aprenda a se perguntar: Se pergunte o que você acabou de ver
  - Aprenda a ensinar: Repita o que você acabou de ver.
- Anotação e Revisão
  - Anote mais após a aula
  - Revise suas anotações e busque respostas para o que você não entendeu

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

<p align="center">

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>
