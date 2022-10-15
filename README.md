# ts-web-template

A development template for working on web apps written in TypeScript/ JavaScript.

Configured with the following tools:

- Typescript support

- Webpack - with a dev server that allows hot loading of changes and that minifies the CSS and JavaScript created for production builds

- ESLint - configured with AirBnb's very popular ruleset and added typescript rules.

- Jest - for testing our application.

## Installation

With node.js and npm installed, just run:
`npm install` to get started.

To start the web server used for development, run:
`npm start`

And to create a production build, run:
`npm run build`

The production build will be located in the /dist folder.
Both the development and production builds use the three index files in src/ as the entry point for the application.
