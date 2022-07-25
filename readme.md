# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Install Docker

Instructions can be found here: [install Docker](https://docs.docker.com/get-docker/)

To verify that Docker is running, by typing `docker-v` and `docker-compose -v` in your terminal.

**From the project root directory** run `docker-compose up` to start the container.

Test that the backend is running by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

Test that the frontend is connected to the backend by creating a new user on [http://localhost:3001/register](http://localhost:3001/register)
