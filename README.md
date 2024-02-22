# fore-project

A blueprint for developing with Fore.

'fore-project' lets you quickly get started with writing your own Fore pages and offers 
end-to-end testing with Cypress. A simple builtin http server allows quick development and testing.

## Requirements

* a reasonably up-to-date nodejs installation on your machine

## Setup

`npm i`

This will download install the dependencies.


## Starting the http server

Open a shell and execute

`npm start`

## Running Cypress

Open a shell and execute

for running Cypress UI: `npx cypress open`
for running in console: `npx cypress run`

## Adding tests

You can add tests manually to the folder 'cypress/e2e' or use the Cypress UI to create new ones.

The configuration comes with a pile of examples which you may delete if they confuse you but they are
a good starter to lookup how things are done in Cypress.

 There's a single `hello.cy.js` right in 'cypress/e2e' as a starter.