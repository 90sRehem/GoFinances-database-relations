<p align="center">
    <img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" style="border-radius:5px;"/>
</p>

<p align="center">
  <img alt="Languages" src="https://img.shields.io/github/languages/count/90sRehem/GoFinances-database-relations">
  <img alt="Top Language" src="https://img.shields.io/github/languages/top/90sRehem/GoFinances-database-relations">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/90sRehem/GoFinances-database-relations">
  <a href="https://github.com/90sRehem/GoFinances-database-relations/commits/master">
    <img alt="Last commit date" src="https://img.shields.io/github/last-commit/90sRehem/GoFinances-database-relations">
  </a>
   <a href="https://github.com/90sRehem/GoFinances-database-relations/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/90sRehem/GoFinances-database-relations">
  </a>
  <img alt="License" src="https://img.shields.io/github/license/90sRehem/GoFinances-database-relations">
</p>

<p align="center">

  <a href="https://www.linkedin.com/in/jonathan-rehem-7101171a5/" target="_blank">
    <img alt="Made by Jonathan Rehem" src="https://img.shields.io/badge/made%20by-Jonathan_Rehem-informational">
  </a>
  <a href="https://github.com/90sRehem" target="_blank" >
    <img alt="Github - Jonathan Rehem" src="https://img.shields.io/badge/Github--%23F8952D?style=social&logo=github">
  </a>
  <a href="https://www.linkedin.com/in/jonathan-rehem-7101171a5/" target="_blank" >
    <img alt="LinkedIn - Jonathan Rehem" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
  </a>
  <a href="mailto:jonathan.de.oliveira@live.com" target="_blank" >
    <img alt="Email - Jonathan Rehem" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
  </a>
</p>

## :rocket: GoFinances-database

<br />
<p align="center">
<img alt="Projeto em funcionamento" src="https://media.giphy.com/media/ic7xxUn6cHB3fJKqEO/giphy.gif">
</p>

## Tecnologias
- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [TSyringe](https://github.com/Microsoft/tsyringe#readme)
- [Express](https://expressjs.com/pt-br/)
- [TypeORM](https://typeorm.io/#/)
- [PostgreSQL](https://www.postgresql.org/)
- [Jest](https://jestjs.io/)
- [SuperTest](https://github.com/visionmedia/supertest)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

## Requerimentos
- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [PostgreSQL](https://www.postgresql.org/)

> obs.: Recomendo usar o docker.

## ⚙️ Instalação

** Clone o repositório e acesse a pasta criada **

```Bash
 $ git clone https://github.com/90sRehem/GoFinances-database.git && cd GoFinances-database
```

```Bash
# Crie uma instância do do postgresSQL usando o docker

$ docker run --name GoFinances-database -e POSTGRES_USER=postgres \
              -e POSTGRES_DB=postgres -e POSTGRES_PASSWORD=docker \
              -p 5432:5432 -d postgres
```

```Bash
# Instale as dependências deste projeto

yarn

```

```Bash
# Uma vez que os serviços estejam sendo executados, rode as migrations

$ yarn typeorm migration:run

# Por fim, inicie a API

yarn dev:server
```

> 🚧 Esta API foi executada com êxito juntamente com o frontend do seguinte repositório: https://github.com/90sRehem/GoFinances, porém pode ser executada utilizando apenas o Insomnia REST Client para fazer as requisições.

> ⚠️ Antes de rodar esta API, crie um banco de dados Postgres com o nome "GoFinances-database" para que todos os testes possam executar corretamente. Para mais informações sobre o banco de dados acesso o arquivo [ormconfig.json](ormconfig.json).

## Licença
[MIT](./LICENSE)

Made with :heart: by <a href="https://www.linkedin.com/in/jonathan-rehem-7101171a5/" target="blank">Jonathan Rehem</a>.
###### Developed on GoStack Bootcamp from [RocketSeat](https://rocketseat.com.br) :rocket:.
