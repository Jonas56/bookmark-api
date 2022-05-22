# Bookmarks REST API

## Description

NestJS REST API where you can CRUD your bookmarks.

### Technologies and tools used

- [Node](https://nodejs.org/en/)
- [NestJs](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [JsonWebToken](https://jwt.io/)
- [Passport](https://www.passportjs.org/)
- [PactumJs](https://pactumjs.github.io/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)

## Getting Started

Clone this repository and install dependencies

```bash
$ git clone git@github.com:Jonas56/bookmark-api.git
$ npm install
```

### Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

### Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Available Endpoints

- **POST** `/signin`
- **POST** `/signup`
- **GET, POST** `/bookmarks`
- **PATCH, DELETE** `/bookmarks/:id`
- **GET** `/users/me`
- **PATCH** `/users`
