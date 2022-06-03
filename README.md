# Cypress issue reproducing repo

This repo was created to reproduce this issue :

## Available Scripts

To reproduce the issue, please :

### `yarn install`

To install the dependencies, then :

### `yarn start`

To run the dev server, then :

### `yarn cypress open`

To create the `coverage` folder, then :

### Reproduce the issue

- Click on "E2E Testing" (configured if necessary)
- Click on "Start E2E Testing in Chrome"
- Click on `spec.cy.ts`

=> You'll see that coverage reports are created and located under `coverage/lcov-report/index.html` file

- Click on "Component Testing"
- Click on "Start Component Testing in Chrome"
- Click on `ComponentName.cy.ts`

=> You'll see a log that tells that "Could not find any coverage information etc..." and also that `coverage/lcov-report/index.html` file is now empty.
