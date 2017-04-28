# Elm + Phoenix
This is a minimum setup for an Elm + Phoenix project, using webpack for bundling.

This is intended to be a teaching tool rather than a boilerplate, therefore the webpack config is as small as possible and a lot of the files that a Phoenix project initialises with have been removed.

Requirements:
- [Phoenix](http://www.phoenixframework.org/docs/installation)
- Node.js/NPM (Install using [nvm](https://github.com/creationix/nvm))

To run:
- `$ npm install`
- `$ npm run build`
- `$ mix deps.get`
- `$ mix phoenix.server`
- Visit http://localhost:4000.

There is also an Elm watch script, `npm run watch`.
