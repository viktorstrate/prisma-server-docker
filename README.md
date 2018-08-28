# Prisma Server Docker

> This repository is a boilerplate, for running a Prisma server behind a GraphQL endpoint for production.

## Featuers

- Automatically reload project, and regenerate `src/generated/prisma.graphql`, on file changes

- Open and flexible when running in a development environment

- Secure and stripped down when building for production

## Running the docker containers

### Development

To start the server in development mode, run `yarn start`, afterwards both GraphQL endpoints can be accessed at [http://localhost:3000/playground](http://localhost:3000/playground).

### Production

To start the server in production mode, run `yarn serve`, afterwards only the secure endpoint will be exposed, and can be accessed at [http://localhost:4000/](http://localhost:4000/).

To stop the server, run `docker-compose down` inside the root directory of the project.