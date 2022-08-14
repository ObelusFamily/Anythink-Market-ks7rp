# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install docker for your OS that you are using.
 
## Second setup

Once docker is installed browse to the root directory and run:
```bash 
docker-compose up
```

## Third setup

Once done browse to: http://localhost:3000/api/ping to see that everything is up and running, if so browse to http://localhost:3001/register to register a new account