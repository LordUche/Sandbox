# iReporter

[![Build Status](https://travis-ci.com/LordUche/sandbox.svg?branch=develop)](https://travis-ci.com/LordUche/sandbox) [![Coverage Status](https://coveralls.io/repos/github/LordUche/sandbox/badge.svg?branch=develop)](https://coveralls.io/github/LordUche/sandbox?branch=develop) [![Maintainability](https://api.codeclimate.com/v1/badges/a50cc56bfadcc52ff4f2/maintainability)](https://codeclimate.com/github/LordUche/sandbox/maintainability)

iReporter enables any/every citizen to bring any form of corruption to the notice of appropriate authorities and the general public. Users can also report on things that needs government intervention

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You must have

1. [Node.js](https://nodejs.org/) (_v10.12.0 or higher_) and NPM (_v6.4.1 or higher_) installed on your local machine. Run `node -v` and `npm -v` in your terminal to confirm that you have them installed

2. A PostgreSQL DBMS installed on your local machine

### Installing

To get started, clone this repository on your local machine using the following steps:

Open your terminal and navigate to the folder you want the project to be and enter the the following commands:

```bash
git clone https://github.com/LordUche/sandbox.git
cd sandbox
npm install
```

Then create a `.env` file and enter values for the `JWT_SECRET` and `DATABASE_URL` environment variables

## Running the tests

```bash
npm test
```

## Deployment

To deploy to Heroku, install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) then run the following commands:

```bash
heroku login
heroku create
git push heroku master
```

## Built With

- [Express](https://expressjs.com/) - The web framework used
- [NPM](https://www.npmjs.com/) - Dependency Management
- [Eslint](https://eslint.org/) - Javascript Linting
- [Babel](https://babeljs.io/) - Javascript compiler
- [Mocha](https://mochajs.org/) - The Javascript test framework used
- [Chai](https://www.chaijs.com/) - BDD/TDD assertion library
- [Istanbul](https://istanbul.js.org/) - Javascript test coverage tool
- [Travis CI](https://travis-ci.com/) - Continuous Integration
- [Coveralls](https://coveralls.io/) - Test coverage
- [Nodemon](https://nodemon.io/) - Code monitoring and automatic server restart utility

## Author

- **Uchenna A. Iheanacho** - _Initial work_ - [Andela](https://andela.com/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Mohammed Isioye
- Stephen Aribaba
