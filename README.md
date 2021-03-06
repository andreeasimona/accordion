# Accordion menu

Accordion menu using Vanila Javascript and Sass

## Table of contents
1. [ Demo ](#demo)
2. [ Install ](#install)
3. [ Run in local enviroment ](#run)
4. [ Deploy ](#deploy)
5. [ Build ](#build)
6. [ Eslinter ](#eslint)
7. [ Unit tests ](#tests)
8. [ Libraries used for development ](#librariesDevelopment)
9. [ Libraries used for testing ](#librariesTesting)

<a name="demo"></a>
## 1. Demo
   https://andreeasimona.github.io/accordion/

<a name="install"></a>
## 2. Install in local enviroment. Before executing any script you should install the npm packages.

   - npm install

<a name="run"></a>
## 3. Run in local enviroment.

   - npm start
   - You can see the content at http://localhost:9000/

<a name="deploy"></a>
## 4. To deploy the project. The project is deployed to the folder docs, used for the gh-page.

   - npm run deploy

<a name="build"></a>
## 5. To build the project in local enviroment

   - npm run build

<a name="eslint"></a>
## 6. For eslint check

   - npm run linter
   The project used the airbnb base javascriopt .eslintrc as an extensible shared config.

<a name="tests"></a>
## 7. For unit tests

   - npm test

<a name="librariesDevelopment"></a>
## 8. Libraries used for development

   - [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) This is a webpack plugin that simplifies  the creation of HTML files to serve your webpack bundles.
   - [node-sass](https://github.com/sass/node-sass) Node-sass is a library that provides binding for Node.js to LibSass. Allows you to natively compile .scss files to css at incredible speed and automatically via a connect middleware.
   - [webpack](https://webpack.js.org/) Webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it internally builds a dependency graph which maps every module your project needs and generates one or more bundles.
   - [webpack-cli](https://webpack.js.org/api/cli/) Command Line Interface for webpack
   - [webpack-dev-server](https://github.com/webpack/webpack-dev-server) Use webpack with a development server that provides live reloading.
   - [babel-core](https://github.com/babel/babel/tree/master/packages/babel-core) Babel compiler core.
   - [babel-loader](https://github.com/babel/babel-loader) This package allows transpiling JavaScript files using Babel and webpack.
   - [babel-plugin-transform-class-properties](https://www.npmjs.com/package/babel-plugin-transform-class-properties) This plugin transforms es2015 static class properties as well as properties declared with the es2016 property initializer syntax.
   - [babel-preset-es2015](https://www.npmjs.com/package/babel-preset-es2015) Babel preset for all es2015 plugins.
   - [babel-register](https://github.com/babel/babel/tree/master/packages/babel-register)

<a name="librariesTesting"></a>
## 9. Libraries used for testing

   - [eslint](https://github.com/eslint/eslint) is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.
   - [eslint-config-airbnb-base](https://github.com/airbnb/javascript) This package provides Airbnb's base JS .eslintrc as an extensible shared config.
   - [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) This plugin intends to support linting of ES2015+ (ES6+) import/export syntax
   - [babel-eslint](https://github.com/babel/babel-eslint) babel-eslint allows you to lint all valid Babel code with the fantastic ESLint.
   - [chai](https://www.chaijs.com/) Chai is a BDD / TDD assertion library for node.js
   - [jsdom](https://github.com/jsdom/jsdom) jsdom is a pure-JavaScript implementation of many web standards, notably the WHATWG DOM and HTML Standards, for use with Node.js.
   - [mocha](https://mochajs.org/) Mocha is a feature-rich JavaScript test framework