# iTunes Search App

Searching app with the iTunes API

## API

- docs: https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/Searching.html#//apple_ref/doc/uid/TP40017632-CH5-SW1

## Client

- Stack: React, Redux, Typescript, Styled Components, Material UI

## Server

- Stack: Node.js, Express

## Running the client app

- in terminal cd into the `client` folder.
  - run `npm i` to install dependencies
  - run `npm start`
  - open browser on http://localhost:3000
- There are some snapshot test and some unit test for the reducer. Ran out of time to test the action

## Serving the static app

- in terminal cd into `client` folder.
  - run `npm run build` to create the app build
- in terminal cd into `server` folder.
  - run `npm i` to install dependencies
  - run npm start
  - open browser on http://localhost:3001
