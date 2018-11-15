# wily

[![PRs Welcome][prs-badge]][prs]
[![MIT License][license-badge]][license]

Build Node.js APIs from the command line

## Getting Started

Install **wily** globally: ``` npm install -g wily ```

Once installed, a new API can be created by calling ```wily init```, like so:

![wily gif](https://media.giphy.com/media/WS4y6MqzqEWcOLxJ88/giphy.gif)

### ✨ Supported & ~~in-progress~~ Features

| API Architecture  | Framework | Database  | ORM | ODM | Authentication | Validation | Testing 
| :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------:
| [REST](https://www.w3.org/2001/sw/wiki/REST)  | [Express](https://www.npmjs.com/package/express)  | [MySQL](https://www.npmjs.com/package/mysql) | [Knex.js](https://www.npmjs.com/package/knex) | ~~[Mongoose](https://www.npmjs.com/package/mongoose)~~ | [JWT](https://www.npmjs.com/package/jsonwebtoken) | [Joi](https://www.npmjs.com/package/joi) | [Mocha](https://www.npmjs.com/package/mocha)
| ~~[GraphQL](https://graphql.org/)~~  | [hapi](https://www.npmjs.com/package/hapi) | ~~[MongoDB](https://www.npmjs.com/package/mongodb)~~  | ~~[Sequelize](https://www.npmjs.com/package/sequelize)~~ | ~~[MongoDB Driver](https://mongodb.github.io/node-mongodb-native)~~ | ~~[express-session](https://www.npmjs.com/package/express-session)~~ <br> ~~[yar (Hapi)](https://www.npmjs.com/package/yar)~~ | ~~[Validator](https://www.npmjs.com/package/validator)~~ | [Jest](https://www.npmjs.com/package/jest)

#### 📦 Built-in Packages

* [Boom](https://www.npmjs.com/package/boom)
* [Dotenv](https://www.npmjs.com/package/dotenv)
* [SuperTest](https://www.npmjs.com/package/supertest)

#### 🤓 Wily Tech

* [TypeScript](https://www.npmjs.com/package/typescript)
* [oclif](https://www.npmjs.com/package/oclif)
* [Inquirer.js](https://www.npmjs.com/package/inquirer)


[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[license-badge]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license]: https://github.com/visionmedia/supertest/blob/master/LICENSE

## Development (Contribute!)

If you're interested in contributing to this project, then THANK YOU! I appreciate your interest :) You can contribute to this project by working on any of the [open issues](https://github.com/alexpereira/wily/issues). You can also see which issues are not in progress on the [development](https://github.com/alexpereira/wily/projects/1) board.

Lastly, I am here to help. Please reach out with any questions. I appreciate all contributions no matter how big or small.

#### Getting Started

- Fork & clone this project
- Next, you will need to [Install TypeScript](https://www.typescriptlang.org/)
- That's it! Now you can compile this project in watch-mode by running ```tsc -w```

#### Testing your contributions*

*I'm still working on unit tests so bear with me for a bit [ISSUE #15](https://github.com/alexpereira/wily/issues/15) (Sorry). In the meantime, I would suggest you test your changes by doing the following:

- Create a temporary tests directory a level up from your copy of ./wily
- Then, from your tests directory, create an ```alias test-wily=../wily/bin/wily```
- Test your changes by running ```test-wily init```

#### Susgested reads:

- [Your first open source contribution: a step-by-step technical guide](https://medium.com/@jenweber/your-first-open-source-contribution-a-step-by-step-technical-guide-d3aca55cc5a6)
- [Visual Studio Code TypeScript Development](https://code.visualstudio.com/docs/languages/typescript)
