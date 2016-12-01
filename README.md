# React ES6 Webpack Karma Boilerplate

Boilerplate for kick starting a project with the following technologies:
* [React](https://github.com/facebook/react)
* [ES6 with Babel](http://babeljs.io)
* [Webpack](http://webpack.github.io) for bundling
* [Webpack Dev Server](http://webpack.github.io/docs/webpack-dev-server.html)
* [React Hot Loader](http://gaearon.github.io/react-hot-loader/) for tweaking React components in real time.
* [Karma](http://karma-runner.github.io/0.13/index.html) for running unit tests.

The various webpack options used have been explained in detailed as comments in the config file. Should help with understanding the nitty-gritty :)

Based on [react-es6-webpack-boilerplate](https://github.com/vasanthk/react-es6-webpack-boilerplate).

### Usage

```bash
npm install
npm start
# Open http://localhost:5000
```

### Linting

ESLint with React linting options have been enabled.

```bash
npm run lint
```

### Testing

Start Karma test runner.

This will run the tests only one, ideal for CI (travis and such).

```bash
npm test
```

This will auto watch all files for changes and rerun the tests. Ideal for development.

```bash
npm run test_watch
```
