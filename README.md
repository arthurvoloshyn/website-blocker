# website-blocker

## To clone

- You'll need to have [git](https://git-scm.com/), [node v16+](https://nodejs.org/en/) and [docker](https://www.docker.com/) installed in
  your system.

`git clone https://github.com/ArturW1998/website-blocker.git`

## Run the project

- Copy `.env.example` as `.env` inside `apps/server`
- Replace the values of the environment variables with your own in the `.env` file
- Run the database with the `npm run db:server` command

```
npm install - install dependencies
npm run start:dev - run server + frontend project in dev mode
```

---

## Scripts

- `npm run dev:client` - Run frontend project
- `npm run start:dev` - Run frontend project + backend
- `npm run start:dev:server` - Run backend server
- `npm run build:client` - Build frontend project in prod mode
- `npm run lint` - Lint check for ts files
- `npm run test:server` - Run backend unit tests with jest
