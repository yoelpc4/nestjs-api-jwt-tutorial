# Nest.js API JWT Tutorial

## Installation

Install project dependencies

```shell
yarn
```

Create .env file with contents

```dotenv
DATABASE_URL="postgresql://postgres:123@localhost:5434/nest?schema=public"
JWT_SECRET=B2kmAda0CFZ6jPzWayrwI2Xi
```

## Running the app

Run database migration

```shell
yarn prisma:dev:deploy
```

Start database container

```shell
yarn db:dev:up
```

Start the application

```shell
yarn start:dev
```

## Test

```shell
yarn test:e2e
```

## Features

- Auth
- User
- Bookmark
