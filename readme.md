# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download Docker from this link : [Download Docker](https://docs.docker.com/docker-for-windows/install/)

2. Verify docker is installed by running docker -v and docker-compose -v.

3. Run docker-compose up in the parent directory to start the backend and frontend.

4. Verify its running by going here: [ping backend](http://localhost:3000/api/ping) and here [register a user](http://localhost:3000/register).