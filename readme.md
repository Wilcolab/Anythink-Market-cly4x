# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Dowmload docker
- From project root directory run `docker-compose up`, to load anythink front-end and back-end
- If the Doceker is working correctly, the backend should be running and able to connect to your local database, test this by pointing your browser to http://localhost:3000/api/ping
- Once the backend is up and running, you'll be able to create a new user on https://localhost:3001/register

- Just make sure that you run all scripts in the next quests on one of the containers created by `docker-compose up`.  Also, you can use `docker exec` to run commands on a running container.