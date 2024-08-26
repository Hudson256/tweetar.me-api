# Tweetar.me API

## Overview

A **Tweetar.me API** fornece os endpoints necessários para alimentar a plataforma de microblogging Tweetar.me. Esta API permite a criação, leitura, atualização e exclusão de tweets, gerenciamento de perfis de usuários, autenticação e outras funcionalidades essenciais para a aplicação.

## Funcionalidades

- **Autenticação de Usuários**: Endpoints para registro, login e gerenciamento de tokens.
- **Gerenciamento de Tweets**: Criação, edição, visualização e exclusão de tweets.
- **Favoritos**: Endpoints para salvar e gerenciar tweets favoritos.
- **Perfis de Usuários**: Endpoints para visualização e edição de perfis de usuários.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução do JavaScript no servidor.
- **Express.js**: Framework para construção da API.
- **Prisma**: ORM para interações com o banco de dados.
- **JWT**: Para autenticação via tokens.
- **PostgreSQL**: Banco de dados relacional utilizado.
- **Docker**: Contêinerização da aplicação.

## Requisitos

- Node.js
- Docker
- Yarn ou NPM
- PostgreSQL

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/Hudson256/tweetar.me-api.git
   cd tweetar.me-api
'''
2. Instale as dependências:

```bash
yarn install
# ou
npm install
```
3. Configure as variáveis de ambiente no arquivo .env, utilizando o exemplo fornecido em .env.example

4. Inicie o Docker:

```bash
docker-compose up -d
```
5.Rode as migrações do Prisma:
```bash
npx prisma migrate deploy
```
6.Inicie o servidor:
```bash
yarn dev
# ou
npm run dev
```
## Testes
O projeto inclui uma suíte de testes para garantir a estabilidade e a qualidade do código. Para rodar os testes, utilize o comando:
```bash
yarn test
# ou
npm run test
```
## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests. Este projeto segue o padrão de código estabelecido por ESLint e Prettier, então certifique-se de rodar o linter antes de submeter suas alterações.

## Licença
Este projeto é licenciado sob a licença MIT.

## Contato
Se você tiver alguma dúvida ou sugestão, entre em contato pelo e-mail: hudsono256@gmail.com.
