# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Pre requisites

* Install [Docker](https://docs.docker.com/get-docker/)
  * Verify that Docker is running with `docker -v` in a terminal
* Run `docker-compose up` from the root of this repo

### Verify things are up and running

* Point your browser to `http://localhost:3000/api/ping`
  * You will get a `pong` when it's working
* Check the frontend by creating a new user on `http://localhost:3001/register`
