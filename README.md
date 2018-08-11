# GraphdataGenerator

This project is a data generator for Graph databases. It allows to generate Cypher queries to create a graph according to the parameters specify by the user.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.4.


## Prerequisites

### Node.js and Tools

- Get [Node.js][node].
- Install the tool dependencies: `npm install`

## Clone the repo

```shell
git clone https://github.com/meganewintz/FastGraph-generator
cd FastGraph-generator
```

### Install npm packages

Install the `npm` packages described in the `package.json` and verify that it works:

```shell
npm install
npm start
```

The `npm start` command builds (compiles TypeScript and copies assets) the application into `dist/`, watches for changes to the source files, and runs `lite-server` on port `3000`.

Shut it down manually with `Ctrl-C`.

## Run the application

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Workings of the Application

- The application filesystem layout structure is based on the [angular-seed][angular-seed] project.
- There is no dynamic backend (no application server) for this application. 

## Application Directory Layout

```
app/                        --> all the source code of the app (along with unit tests)
  data-parameters-form/...  --> files for the 'form page' component (the only one page currently)
  data_parameters_model.ts  --> class 'DataParameter' to represent all the parameters available.
  app.config.js             --> app-wide configuration of Angular services
  app.css                   --> default stylesheet
  app.module.js             --> the main app module
  index.html                --> app layout file (the main HTML template file of the app)

node_modules/...            --> development tools (fetched using `npm`)

karma.conf.js               --> config file for running unit tests with Karma
package.json                --> Node.js specific metadata, including development tools dependencies
```

