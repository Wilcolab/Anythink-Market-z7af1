# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker either using binaries or with Docker Desktop:

[https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

2. Clone the repository:

```sh
git clone <enter_git_repo>
```

3. Start the application, along with the database using `docker compose up`.

4. Verify the backend is working by going to [http://localhost:3000/api/ping](http://localhost:3000/api/ping).
You should see some JSON coming back that looks something like: `{"msg":"Pong! Seems like Everythink is working, great job!"}`

5. Verify the frontend is working by going to [http://localhost:3001](http://localhost:3001). You should see a webpage with sign up form.
