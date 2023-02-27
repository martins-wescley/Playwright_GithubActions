# Testes _end-to-end_ com Playwright

Sample project to demonstrate end-to-end (e2e) tests written with Playwright running on a CI service.

## Pre-requirements

To run this project, you will need:

- [git](https://git-scm.com/downloads) 
- [nodejs](https://nodejs.org/en/) 
- NPM 
- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)
- [Google Chrome](https://www.google.com/intl/en_us/chrome/) 

**Note:** When installing nodejs, NPM is automatically installed too.

## Installation 

### Api
Navigate to api folder and install the dev dependencies, run `yarn install`

### Web
Navigate to web folder and install the dev dependencies, run `yarn install`

### Playwright
1. In the root directory install the dev dependencies, run `yarn install`
2. In the same directory install the test browser, `yarn playwright install chromium` 

## Starting the test environment
1. In a terminal, navigate to api folder and execute the command `yarn dev`
2. In another terminal, navigate to web folder and execute the command `yarn dev`

## Running the tests

In this project, you can run tests in debug and headless modes.

### Headless mode

Run `yarn playwright test` to run all tests in headless mode.

### Debug mode

Run `yarn playwright test --debug` to open the Playwrigth Inspector and a browser window highlighting the elements as you step through each line of test.

___
Made by [Wescley Martins](https://github.com/martins-wescley).
