# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Set up local environment
1. Pull the repo by issuing the command `git clone https://github.com/ObelusFamily/Anythink-Market-51k3g.git`
2. Install Docker and Docker Compose
3. Confirm they are installed by running `docker -v` and `docker-compose -v`
4. Change to the repo directory and run `docker-compose up`
5. Verify you can connect to the local database by pointing your browser to http://localhost:3000/api/ping
6. Create a test user at http://localhost:3001/register
