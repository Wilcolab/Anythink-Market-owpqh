# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

<<<<<<< HEAD
## How to run locally?
1. [Install Docker](https://docs.docker.com/get-docker/)
2. [Install Docker Compose](https://docs.docker.com/compose/install/)
3. Run `docker-compose up`. 
=======
## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Install Docker for your OS from the official site: https://docs.docker.com/get-docker/

Verify docker is ready by running the following commands in your terminal:
docker -v
docker-compose -v
Then, run the following command from the projects root folder: docker-compose up

If Docker is working correctly, the backend should be running and able to connect to your local database.
Let's test this by pointing your browser to http://localhost:3000/api/ping

Check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

Please be sure to run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.
>>>>>>> 8352de87b93ac2d0f0674f23b021f69015efc758
