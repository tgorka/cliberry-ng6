# <%= name %>

[![Version npm](https://img.shields.io/npm/v/<%= utils.dasherize(name) %>.svg)](https://www.npmjs.com/package/<%= utils.dasherize(name) %>)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT) 
[![Github Downloads](https://img.shields.io/github/downloads/tgorka/<%= utils.dasherize(name) %>/total.svg)](https://github.com/tgorka/<%= utils.dasherize(name) %>)
[![NPM Downloads](https://img.shields.io/npm/dt/<%= utils.dasherize(name) %>.svg)](https://www.npmjs.com/package/<%= utils.dasherize(name) %>)
[![NPM Gziped size](https://img.shields.io/bundlephobia/minzip/<%= utils.dasherize(name) %>.svg)](https://www.npmjs.com/package/<%= utils.dasherize(name) %>)
[![Dependency Status](https://david-dm.org/tgorka/<%= utils.dasherize(name) %>.svg)](https://david-dm.org/tgorka/<%= utils.dasherize(name) %>)
[![Build Status](https://travis-ci.org/tgorka/<%= utils.dasherize(name) %>.svg?branch=master)](https://travis-ci.org/tgorka/<%= utils.dasherize(name) %>)
[![Coverage percentage](https://coveralls.io/repos/tgorka/<%= utils.dasherize(name) %>/badge.svg)](https://coveralls.io/r/tgorka/<%= utils.dasherize(name) %>)


<%= description %>

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.1.

This repository is a basic web app implementation that serves as a starting point to create and publish Schematics to NPM.
This web app contains:
* angular 6.1
* debug framework
* yarn 
* yarn lock file
* onpush angular strategy
* angular elements
* scss
* tests (jasmine, protractor - defaults)
* lint
* package the output into single bundle
* code build
* IDEA config 
* editorconfig
* gitignore
* README

## Table of Contents

* [Build](#build)
* [Development server](#development-server)
* [Code scaffolding](#code-scaffolding)
* [Running unit tests](#running-unit-tests)
* [Running end-to-end tests](#running-end-to-end-tests)
* [Running linter](#running-linter)
* [Publishing](#publishing)
* [Further help](#further-help)

### Build

to build the project use build command:

```batch
yarn build
```

or 

```batch
npm run build
```

and to create the bundle after the build:

```batch
yarn package
```

or 

```batch
npm run package
```

The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

The generated project will use the web component of the name: `<<%= utils.dasherize(name) %>></<%= utils.dasherize(name) %>>`

After including generated project bundle with name: `<%= utils.dasherize(name) %>.min.js`

To develop the project you can import it into the InteliJ IDEA (or Web Storm) IDE 
and use defined targets to run the project.

Or use `yarn/npm` to `run/test/lint` the project

### Development server

Run `yarn start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `cliberry g component component-name` to generate a new component. You can also use `cliberry generate directive|pipe|service|class|guard|interface|enum|module`.

### Running unit tests

Run `yarn test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `yarn e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Running linter

Run `yarn lint` to execute the linter checks via [TSLint](https://palantir.github.io/tslint/)

### Publishing

To publish, simply do:

```bash
yarn build
yarn publish
```

```bash
npm run build
npm publish
```

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

