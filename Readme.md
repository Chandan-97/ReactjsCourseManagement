## Usage

React => Component
React Router => Routing
Flux => Data flow

## React Router

Client-side Router
Instantaneous Page Transition
Declarative
Nested views map to nested routes -> Nesting route that help to make deep layer complex routing possible

## Flux

Unidirectional data flows
Updates flow in one direction
Easy to debug and scale
More of a pattern than a library

## Webpack

Bundler
Use npm packages on web apps
Bundles styles images and more.

## Eslint

Linter that checks for coding error issues and best practices.
It can be extended for features but default is also good enough to use.

## Why React

Fast, Composable, simple, proven.
JSX, virtual DOM

## Core Technologies

React -Components
React Routing -Routing
Flux -Data flow
Node npm -Package/Automation
Babel -Transpile
Webpack -Bundle
Eslint -Lint

# Environment Setup

Install Node
Install Vscode
Configure Prettier -> Auto format the code
Run create-react-app
Install - React Router -Routing - Flux -State Management - Bootstrap -Styling
Configure Mock API to be used for the application

# Create React App with create-react-app

====

- `npx create-react-app@3.0.1 ps-flux`
- `npm install flux@3.1.3 react-router-dom@5.0.0 bootstrap@4.3.1`

## Why Mock API

Start before the API exist
Independence
Backup plan
Ultra-fast
Test Slowness
Aids Testing
Point to real API later

## Creating Mock API

We'll be using json server.
`npm install -D cross-env@5.2.0 npm-run-all@4.1.5 json-server@0.15.0`
cross-env is used for setting environment variables
npm-run-all is used to run multiple scripts
json-server will serve our mock data

## React Core Concepts

React is a simple composable component library
M -React state handles the Model
V -React works with frontend
C -Components can have some logic

React handles markups through JSX.
It is a xml like syntax called JSX.
It's almost like HTML, it's not HTML but almost like HTML, instead with minor difference.
Babel compiles JSX to javascript.
With virtual DOM compare current state with desired new state and update DOM in most efficient way.

React offers synthetic events
Synthetic events abstract out browser specific event cores and allow react to optimize the performance.
It's like if we attach event listener in each row of the table then react will automatically attach listener to the highest level for performance reason.
Isomorphic support
React Native -> Implement react in native application, where the DOM doesn't exist.
