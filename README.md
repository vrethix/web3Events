# fee-collector-events

![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)

## Description

This project is a fee collector for events, built using TypeScript, Express, Mongoose, ethersXzc

## Installation

Before running the project, make sure you have Node.js and npm installed.

```bash
npm install
````

## Scripts

Run tests:

```bash
npm test
```

Run the development server:

```bash
npm run dev
```

Build the project:

```bash
npm run build
```

Start the server:

```bash
npm start
```

## Dependencies

- mongoDB : Install MongoDB compass locally or change the url in config file
- typegoose: TypeScript compatible ODM for MongoDB and Node.js
- ethers: A library for interacting with the Ethereum blockchain
- express: Fast, unopinionated, minimalist web framework for Node.js
- mongoose: MongoDB object modeling for Node.js
- node-cron: A simple cron-like library for Node.js
- supertest: HTTP assertion library for testing Express apps
- winston: A versatile logging library for Node.js

## Dev Dependencies

- @types/express: TypeScript types for Express
- @types/jest: TypeScript types for Jest
- @types/node-cron: TypeScript types for node-cron
- jest: JavaScript testing framework
- ts-jest: TypeScript preprocessor for Jest
- ts-node: TypeScript execution and REPL for Node.js

## Rest Endpoint API
- http://localhost:4000/events/integratorAddress   [Example below]
- http://localhost:4000/events/0x1aC3EF0ECF4E0ed23D62cab448f3169064230624

## Tests

- There are total 6 tests, 4 tests are successfully passed
