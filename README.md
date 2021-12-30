<br />
<p align="center">
  <a href="https://github.com/Diones25/crud-node">
    <img src="./assets/node.png" alt="Logo" height="300">
  </a>

  <h3 align="center">CRUD NODE JS</h3>

  <p align="center">
    Tecnologias utilizadas: Typescript, Typeorm, Routing Controllers e PostgreSQL
    <br />
  </p>
</p>

## Descrição:
> Este projeto é um CRUD  básico que lista categorias de vídeos, sendo possível adicionar, atualizar e remover as categorias, além disso o usuário pode adicionar um nome de um vídeo, duração, descrição, e uma data de criação que é adicionada automaticamente, quando o video é criado ele cria uma chave estrangeira que liga a categoria selecionada, e também é possível listar os vídeos com a categoria associada.


## Requisitos:

- `nodejs`
- `postgres`

## Como executar:

> antes de executar, certifique-se de atualizar o arquivo `.env` na raiz do projeto com as variaveis do seu ambiente e atualize o banco de dados com as migrações com o comando: `yarn migration:run`, após isso rode os comandos abaixo:

```sh
npm install
yarn dev