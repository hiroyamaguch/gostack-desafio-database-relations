# Desafio GoStack - Database Relations
Diretório do projeto original nest [link](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-database-relations).

# Sobre o projeto
Este back-end foi desenvolvido para o desafio Database Relations do curso GoStack da Rocketseat e tem por objetivo trabalhar os conceitos de TypeORM e ManyToMany

# Tecnologias utilizadas
- JavaScript / TypeScript
- [Node.js](https://nodejs.org/en/)
- [Jest](https://jestjs.io/pt-BR/)
- [Express](https://expressjs.com/pt-br/)
- [Eslint](https://eslint.org/)
- [PostgreSQL](https://www.postgresql.org/)

# Como executar o projeto
Pré-requisitos: npm / yarn

```bash
# Clone este repositório
git clone https://github.com/hiroyamaguch/gostack_challenge_8.git

# Acesse a pasta do projeto no terminal/cmd
cd gostack_challenge_8

# Instale as dependências
$ yarn
# ou
$ npm install

# Configure a variável de ambiente com a url do banco de dados no 
# arquivo .env.example. Depois renomeie o arquivo para .env e salve as alterações

# Execute as migrations
$ yarn typeorm migration:run
# ou
$ npm run typeorm migration:run

# Execute o projeto
$ yarn dev:server
# ou
$ npm run dev:server
```

# Autor

Pedro Antônio Hiroyuki Yamaguchi

https://www.linkedin.com/in/hiroyamaguch/
