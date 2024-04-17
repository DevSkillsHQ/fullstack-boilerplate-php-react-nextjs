# Fullstack Boilerplate

A backbone for your coding challenge.

## Contents

- [Backend service](app-backend) - a Laravel service with a `/ping` endpoint. Extend with your code.
- [Frontend app](app-frontend) - a React/NextJS app. Extend with your code.
- [E2E test suites](cypress/integration) - a backend and a frontend Cypress test suites. Extend with your tests.
- [Pipeline](.github/workflows/tests.yml) - a test Runner that executes the Cypress tests on push to a branch other than `master`/`main`.

## Tech Stack

### Backend

- PHP 8.0.28,
- Laravel Framework 9.52.9

#### Additional libs

- sqlite3 (SQLite connection)
  
### Frontend

- NextJS
- React

### Misc

- Cypress
- GitHub Actions

## Getting started

1. Make sure the required version of PHP (8.0) and Laravel Framework (9.52) is configured on your local env.

2. Make sure npm & node are configured on your local env. You can download those distributions for your platform [here](https://nodejs.org/en/download/)

3. Build your app.

```bash
npm install
npm run build # both Laravel backend and NextJS frontend
npm run build:backend # only Laravel backend
npm run build:frontend # only NextJS frontend
```

4. Start your app.

```bash
npm install
npm run start # both Laravel backend and NextJS frontend
npm run start:backend # only Laravel backend
npm run start:frontend # only NextJS frontend
```

5. Run the Cypress tests.

```bash
npm run test # run project tests under `cypress/integration`
```

---

Made by [Alva Labs](https://alvalabs.io).
