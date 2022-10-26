# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone to repo into a file of your choice.
2. Then, open the cloned repo in your IDE of choice.
3. Open the terminal, and run `docker compose up` - this may take a while.
4. Once that has completed, visit `http://localhost:3000/api/ping` - you should see some text that looks like `{"msg":"Pong! Seems like Everythink is working, great job!"}`.
5. Then, visit `http://localhost:3001/register` and sign up!

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
