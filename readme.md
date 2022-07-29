# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

It's required to have [Docker](https://docs.docker.com/get-docker/) to run the project.

To start the project with docker-compose:

```sh
docker-compose up
```

To stop the project:

```sh
docker-compose down
```

The frontend will up on port 3001: 

http://localhost:3001/

The backend will up on port 3000:

http://localhost:3000/
