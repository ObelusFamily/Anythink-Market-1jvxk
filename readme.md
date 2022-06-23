# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repository to your local machine using `git clone <HTTPS clone link>`
2. Install [Docker](https://docs.docker.com/get-docker/)
3. You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
4. From the project root directory(The cloned repository on your local machine) run `docker-compose up`
5. Test the backend by pointing your browser to http://localhost:3000/api/ping
6. Check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on             http://localhost:3001/register
7. That's it the setup is done.
