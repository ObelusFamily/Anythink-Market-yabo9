# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Steps

1. Install Docker
2. Verify that docker is installed correctly

- run `docker -v`
- run `docker-compose -v`

3. Run `docker-compose up` from the project's root directory
4. Ping backend to verify it's running

- http://localhost:3000/api/ping

5. Register user to verify frontend is running and connected to backend

- http://localhost:3001/register
