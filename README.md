[![Build Status](https://dev.azure.com/twidel/Workcation%20Tailwind%20Angular/_apis/build/status/Workcation%20Angular?branchName=master)](https://dev.azure.com/twidel/Workcation%20Tailwind%20Angular/_build/latest?definitionId=36&branchName=master)

# Workcation Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Run in docker locally with live reload
To build the docker image run `docker build -t <name>:<version> .`
To run the docker image in a container `docker run -v ${PWD}:/app -v /app/node_modules -p 4200:4200 --rm <name>:<version>`

Go to http://localhost:4200 :)
