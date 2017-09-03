# Start the challenge of the Risingstack nodejs bootcamp

[blog How Do I Survived RisingStack's Nodejs's Bootcamp ](https://blog.risingstack.com/node-js-bootcamp)

# Installation

## Install Node 8 and the the latest npm
use nvm to manage the multiple version of the nodejs
the stable version is 6.11 and the latest is 8.4.0

## Postgres and the  GUI tools

$brew install postgresql

$brew install pgweb

# Steps
## 1. Create the simple web application and make the test pass

Tasks:
* create a GET endpoint /hello returning Hello Nodejs! int the response body, use the middleware of the koa-router pakcage
* use the PORT environment variable to set the port make it required
*make the test pass (npm run test-web)
* RUn the application(eg. PORT=3000 npm start and try if it breaks whe PORT is not provided)

Materials:
* [12 factor - config](https://12factor.net/config)
* [Node process](https://nodejs.org/api/process.html)
* [Koa web framework](https://koajs.com)
* [Koa Router](https://github.com/alexmingoia/koa-router)
* [Mocha test framework](https://mochajs.org)
* [Chai assertion library](https://chaijs.com/api/bdd)

