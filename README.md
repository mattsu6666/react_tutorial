## React Starter Kit — "isomorphic" web app boilerplate

[![Support us on Bountysource](https://dl.dropboxusercontent.com/u/16006521/react-starter-kit/banner.png)](https://salt.bountysource.com/teams/react-starter-kit)<br>

> [React Starter Kit](https://www.reactstarterkit.com) is an opinionated
> boilerplate for web development built on top of Facebook's
> [React](https://facebook.github.io/react/) library,
> [Node.js](https://nodejs.org/) / [Express](http://expressjs.com/) server
> and [Flux](http://facebook.github.io/flux/) architecture. Containing
> modern web development tools such as [Webpack](http://webpack.github.io/),
> [Babel](http://babeljs.io/) and [BrowserSync](http://www.browsersync.io/).
> Helping you to stay productive following the best practices. A solid starting
> point for both professionals and newcomers to the industry.

See [demo](http://demo.reactstarterkit.com) &nbsp;|&nbsp;
[docs](https://github.com/kriasoft/react-starter-kit/tree/master/docs) &nbsp;|&nbsp;
[to-do list](https://waffle.io/kriasoft/react-starter-kit) &nbsp;|&nbsp;
join [#react-starter-kit](https://gitter.im/kriasoft/react-starter-kit) chatroom to stay up to date &nbsp;|&nbsp;
visit our sponsors:

[![Rollbar - Full-stack error tracking for all apps in any language](https://dl.dropboxusercontent.com/u/16006521/react-starter-kit/rollbar.png)](https://rollbar.com/?utm_source=reactstartkit(github)&utm_medium=link&utm_campaign=reactstartkit(github)) &nbsp;&nbsp;
[![Localize - Translate your web app in minutes](https://dl.dropboxusercontent.com/u/16006521/react-starter-kit/localize.png)](https://localizejs.com/?cid=802&utm_source=rsk)

### Getting Started

  * Follow the [getting started guide](./docs/getting-started.md) to download and run the project
  * Check the [code recipes](./docs/recipes) used in this boilerplate, or share yours

### Directory Layout

```
.
├── /build/                     # アウトプットディレクトリ
├── /docs/                      # ドキュメント
├── /node_modules/              # サードパーティNodeモジュール
├── /src/                       # ソースディレクトリ
│   ├── /actions/               # Action creators that allow to trigger a dispatch to stores
│   ├── /components/            # React components
│   ├── /constants/             # Constants (action types etc.)
│   ├── /content/               # Static content (plain HTML or Markdown, Jade, you name it)
│   ├── /core/                  # Core framework and utility functions
│   ├── /data/                  # GraphQL server schema
│   ├── /decorators/            # Higher-order React components
│   ├── /public/                # Static files which are copied into the /build/public folder
│   ├── /stores/                # Stores contain the application state and logic
│   ├── /views/                 # Express.js views for index and error pages
│   ├── /client.js              # Client-side startup script
│   ├── /config.js              # Global application settings
│   ├── /routes.js              # Universal (isomorphic) application routes
│   └── /server.js              # Server-side startup script
├── /tools/                     # Build automation scripts and utilities
│   ├── /lib/                   # Library for utility snippets
│   ├── /build.js               # Builds the project from source to output (build) folder
│   ├── /bundle.js              # Bundles the web resources into package(s) through Webpack
│   ├── /clean.js               # Cleans up the output (build) folder
│   ├── /copy.js                # Copies static files to output (build) folder
│   ├── /deploy.js              # Deploys your web application
│   ├── /run.js                 # Helper function for running build automation tasks
│   ├── /runServer.js           # Launches (or restarts) Node.js server
│   ├── /start.js               # Launches the development web server with "live reload"
│   └── /webpack.config.js      # Configurations for client-side and server-side bundles
│── package.json                # Nodeモジュールの管理用ファイル
└── preprocessor.js             # Jest用ES6トランスパイラES6(Jestはテストフレームワーク．トランスパイラはES5用コードにコンパイルする)
```

### Related Projects

  * [Membership Database](https://github.com/membership/membership.db) — SQL schema boilerplate for user accounts, profiles, roles, and auth claims
  * [React Static Boilerplate](https://github.com/koistya/react-static-boilerplate) — Generates static websites from React components
  * [Babel Starter Kit](https://github.com/kriasoft/babel-starter-kit) — Boilerplate for authoring JavaScript/React.js libraries

### Learn More

  * [Getting Started with React.js](http://facebook.github.io/react/)
  * [Getting Started with GraphQL and Relay](https://quip.com/oLxzA1gTsJsE)
  * [React.js Questions on StackOverflow](http://stackoverflow.com/questions/tagged/reactjs)
  * [React.js Discussion Board](https://discuss.reactjs.org/)
  * [Flux Architecture for Building User Interfaces](http://facebook.github.io/flux/)
  * [Jest - Painless Unit Testing](http://facebook.github.io/jest/)
  * [Flow - A static type checker for JavaScript](http://flowtype.org/)
  * [The Future of React](https://github.com/reactjs/react-future)
  * [Learn ES6](https://babeljs.io/docs/learn-es6/), [ES6 Features](https://github.com/lukehoban/es6features#readme)

### Support

  * [#react-starter-kit](http://stackoverflow.com/questions/tagged/react-starter-kit) on Stack Overflow — Questions and answers
  * [#react-starter-kit](https://gitter.im/kriasoft/react-starter-kit) on Gitter — Watch announcements, share ideas and feedback
  * [GitHub issues](https://github.com/kriasoft/react-starter-kit/issues), or [Scrum board] — File issues, send feature requests
  * [appear.in/react](https://appear.in/react) — Open hours! Exchange ideas and experiences (React, GraphQL, Startups, etc.)
  * [@koistya](https://twitter.com/koistya) on [Codementor](https://www.codementor.io/koistya), or [Skype](http://hatscripts.com/addskype?koistya) — Private consulting

### License

Copyright © 2014-2016 Kriasoft, LLC. This source code is licensed under the MIT
license found in the [LICENSE.txt](https://github.com/kriasoft/react-starter-kit/blob/master/LICENSE.txt)
file. The documentation to the project is licensed under the
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) license.

---
Made with ♥ by Konstantin Tarkus ([@koistya](https://twitter.com/koistya)) and [contributors](https://github.com/kriasoft/react-starter-kit/graphs/contributors)
