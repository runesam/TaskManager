# Introduction

Using your application we must be able to create, modify and delete a task.

## How does it work?

* Application meant to run in the server side.
* Next.js been used to handle the SSR.
* Tests been included with in the dev process as TDD.

## Installation
    npm i
    
#### For running the app with tests
    npm start

#### For running the app without tests
    npm run dev
    
## Find in the app
* Next.js for SSR
* Redux for state management
* Redux Saga for handling side effects
* Socket.io
* Mocha as test framework
* Enzyme to test react component

## Notes
* The app is not fully dynamic. Only the updates been developed so as a sample.
* Integration tests with saga are very expensive in terms of time. One only been handled so far.
* Form validation is not perfect.