# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Please follow the next steps to start setting up your dev environment:

- Install Docker, which is going to make it easier for us to run things locally.
  - To veryfy the installation is successfull run in your terminal `docker -v` and `docker-compose -v`
- Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
  - Test it pointing your browser to: [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
    - It will show a response message like this: `{"msg":"Pong! Seems like Everythink is working, great job!"}`
  - To check if the frontend is connected to the backend, create a user in: [http://localhost:3001/register](http://localhost:3001/register)
- You can use `docker exec` to run commands on a running container.

Your environment is now ready!! Congrats! 🙂
