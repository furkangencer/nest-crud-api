## Description

Simple CRUD API Using NestJS, MongoDB and Docker. It exposes 5 main endpoints:

* <b style="color:green">GET</b> /users
* <b style="color:green">GET</b> /users/:id
* <b style="color:orange">POST</b> /users
* <b style="color:gray">PATCH</b> /users/:id
* <b style="color:red">DELETE</b> /users/:id

## Usage

Create `.env` file at project's root directory and specify your mongodb connection string there. (see `.enx.example`)

Run the command below and docker will serve the API on port 3000.

```bash
$ docker-compose up -d --build nest_user_service
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
