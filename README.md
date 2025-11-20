# Cypress, from Zero to the cloud

<!-- [![main](https://github.com/wlsf82/cy-data-test/actions/workflows/ci.yml/badge.svg)](https://github.com/wlsf82/cy-data-test/actions) -->

Sample project for the "Cypress, from Zero to the cloud" course of the Talking About Testing online school.

## Pre-requirements

It is required to have git, Node.js and npm installed to clone and run this project.

> I used versions `2.35.1`, `v22.14.0` and `10.2.0` of git, Node.js and npm, respectively. I suggest you use the same or later LTS versions.

## Installation

Run `npm install` (or `npm i` for the short version) to install the dev dependencies.

## Tests

In This project, you can run the tests on a desktop or mobile viewport.

<!-- > **Note:** Before running the tests, make a copy of the `cypress.env.example.json` file as `cypress.env.json`, which in the real world, you would update with valid credentials.
>
> The `cypress.env.json` file is included on [`.gitignore`](./.gitignore) and you're safe that confidential info won't be versioned. -->

### Desktop

Run `npm test` (or `npm t` for the short version) to run the test in headless mode on a desktop viewport.

Or, run `npm run cy:open` to open Cypress App on a desktop viewport.

### Mobile

Run npm run test:mobile to run the test in headless mode on a mobile viewport.

Or, run npm cy:open:mobile to open the Cypress app on mobile viewport.

___

<!-- This project was created with 💚 by [Walmyr](https://walmyr.dev). -->