# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sorrycc/awesome-javascript/)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

<details>

<summary>Contents</summary>

* [Package Managers](#package-managers)
* [Component management](#component-management)
* [Loaders](#loaders)
* [Transpilers](#transpilers)
* [Bundlers](#bundlers)
* [Minimizers](#minimizers)
* [Type Checkers](#type-checkers)
* [Testing Frameworks](#testing-frameworks)
* [QA Tools](#qa-tools)
* [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
* [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
* [Templating Engines](#templating-engines)
* [Game Engines](#game-engines)
* [Articles/Posts](#articles-and-posts)
* [Data Visualization](#data-visualization)
  * [Timeline](#timeline)
  * [Spreadsheet](#spreadsheet)
* [Editors](#editors)
* [Documentation](#documentation)
* Utilities
  * [Files](#files)
  * [Functional Programming](#functional-programming)
  * [Reactive Programming](#reactive-programming)
  * [Data Structure](#data-structure)
  * [Date](#date)
  * [String](#string)
  * [Number](#number)
  * [Storage](#storage)
  * [Color](#color)
  * [I18n And L10n](#i18n-and-l10n)
  * [Control Flow](#control-flow)
  * [Routing](#routing)
  * [Security](#security)
  * [Log](#log)
  * [RegExp](#regexp)
  * [Media](#videoaudio)
  * [Voice Command](#voice-command)
  * [API](#api)
  * [Streaming](#streaming)
  * [Vision Detection](#vision-detection)
  * [Browser Detection](#browser-detection)
  * [Operating System](#operating-system)
  * [Benchmark](#benchmark)
  * [Machine Learning](#machine-learning)
  * [Web Worker](#web-worker)
* UI
  * [Code Highlighting](#code-highlighting)
  * [Loading Status](#loading-status)
  * [Validation](#validation)
  * [Keyboard Wrappers](#keyboard-wrappers)
  * [Tours And Guides](#tours-and-guides)
  * [Notifications](#notifications)
  * [Sliders](#sliders)
  * [Range Sliders](#range-sliders)
  * [Form Widgets](#form-widgets)
  * [Tips](#tips)
  * [Modals and Popups](#modals-and-popups)
  * [Scroll](#scroll)
  * [Menu](#menu)
  * [Table/Grid](#tablegrid)
  * [Frameworks](#frameworks-1)
  * [Boilerplates](#boilerplates)
  * [Images](#images)
* [Gesture](#gesture)
* [Maps](#maps)
* [Typography](#typography)
* [Animations](#animations)
* [Image processing](#image-processing)
* [ES6](#es6)
* [Generators](#generators)
* [Full Text Search](#full-text-search)
* [SDK](#sdk)
* [ORM](#orm)
* [WebSockets](#websockets)
* [Misc](#misc)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

</details>

----

## Package Managers
*Host the JavaScript libraries and provide tools for fetching and packaging them.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [npm](https://npmjs.com) | [npm/cli](https://github.com/npm/cli) | the package manager for JavaScript. | ![GitHub](https://img.shields.io/github/stars/npm/cli) |
| [Bower](https://bower.io) | [bower/bower](https://github.com/bower/bower) | A package manager for the web. | ![GitHub](https://img.shields.io/github/stars/bower/bower) |
| [jspm](https://jspm.org) | [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | Import Map Package Manager. | ![GitHub](https://img.shields.io/github/stars/jspm/jspm-cli) |
| [yarn](https://yarnpkg.com) | [yarnpkg/berry](https://github.com/yarnpkg/berry) | Fast, reliable, and secure dependency management. | ![GitHub](https://img.shields.io/github/stars/yarnpkg/berry) |
| [pnpm](https://pnpm.io) | [pnpm/pnpm](https://github.com/pnpm/pnpm) | Fast, disk space efficient package manager. | ![GitHub](https://img.shields.io/github/stars/pnpm/pnpm) |
| [bun](https://bun.com) | [oven-sh/bun](https://github.com/oven-sh/bun) | Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one | ![GitHub](https://img.shields.io/github/stars/oven-sh/bun) |


## Component Management

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Bit](https://bit.dev) | [teambit/bit](https://github.com/teambit/bit) | AI-powered development workspaces with reusable components, architectural clarity and zero overhead. | ![GitHub](https://img.shields.io/github/stars/teambit/bit) |


## Loaders
*Module or loading system for JavaScript.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [RequireJS](https://requirejs.org/) | [requirejs/requirejs](https://github.com/requirejs/requirejs) | A file and module loader for JavaScript. | ![GitHub](https://img.shields.io/github/stars/requirejs/requirejs) |
| [browserify](http://browserify.org/) | [browserify/browserify](https://github.com/browserify/browserify) | browser-side require() the node.js way. | ![GitHub](https://img.shields.io/github/stars/browserify/browserify) |
| [SystemJS](https://github.com/systemjs/systemjs) | [systemjs/systemjs](https://github.com/systemjs/systemjs) | Dynamic ES module loader. | ![GitHub](https://img.shields.io/github/stars/systemjs/systemjs) |


## Transpilers
*Software that converts the modern JavaScript syntax into the older JavaScript syntax.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [SWC](https://swc.rs/) | [swc-project/swc](https://github.com/swc-project/swc) | Rust-based platform for the Web. | ![GitHub](https://img.shields.io/github/stars/swc-project/swc) |


## Bundlers

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [webpack](https://webpack.js.org) | [webpack/webpack](https://github.com/webpack/webpack) | A bundler for javascript and friends. | ![GitHub](https://img.shields.io/github/stars/webpack/webpack) |
| [Rollup](https://rollupjs.org/) | [rollup/rollup](https://github.com/rollup/rollup) | Next-generation ES module bundler. | ![GitHub](https://img.shields.io/github/stars/rollup/rollup) |
| [Parcel](https://parceljs.org) | [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | The zero configuration build tool for the web. | ![GitHub](https://img.shields.io/github/stars/parcel-bundler/parcel) |
| [Microbundle](https://npm.im/microbundle) | [developit/microbundle](https://github.com/developit/microbundle) | Zero-configuration bundler for tiny modules. | ![GitHub](https://img.shields.io/github/stars/developit/microbundle) |
| [bundlejs](https://bundlejs.com) | [okikio/bundlejs](https://github.com/okikio/bundlejs) | An online tool to quickly bundle & minify your projects, while viewing the compressed gzip/brotli bundle size, all running locally on your browser. | ![GitHub](https://img.shields.io/github/stars/okikio/bundlejs) |
| [Vite](https://vite.dev) | [vitejs/vite](https://github.com/vitejs/vite) | Next generation frontend tooling. It's fast! | ![GitHub](https://img.shields.io/github/stars/vitejs/vite) |


## Minimizers

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Terser](https://terser.org) | [terser/terser](https://github.com/terser/terser) | JavaScript parser, mangler and compressor toolkit for ES6+. | ![GitHub](https://img.shields.io/github/stars/terser/terser) |
| [UglifyJS](http://lisperator.net/uglifyjs) | [Uglify](https://github.com/mishoo/UglifyJS) | JavaScript parser / mangler / compressor / beautifier toolkit. | ![GitHub](https://img.shields.io/github/stars/mishoo/UglifyJS) | 


## Type Checkers

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [TypeScript](https://www.typescriptlang.org/) | - | A typed superset of JavaScript that compiles to plain JavaScript. |  |
| [Flow.js](https://flow.org/) | - | A static type checker for JavaScript from Facebook. |  |
| [Hegel](https://hegel.js.org/) | - | A static type checker for JavaScript with a bias on type inference an strong type system. |  |
| [TypL](https://github.com/getify/TypL) | [getify/TypL](https://github.com/getify/TypL) | the JavaScript Type Linter with a bias on type inference. | ![GitHub](https://img.shields.io/github/stars/getify/TypL) |
| [Hindley Milner Definitions](https://github.com/xodio/hm-def) | [xodio/hm-def](https://github.com/xodio/hm-def) | runtime type checking for JavaScript functions using Haskell-alike Hindley Milner type signatures. | ![GitHub](https://img.shields.io/github/stars/xodio/hm-def) |
| [Zod](https://github.com/colinhacks/zod) | [colinhacks/zod](https://github.com/colinhacks/zod) | TypeScript-first schema validation with built-in static type inference. | ![GitHub](https://img.shields.io/github/stars/colinhacks/zod) |


## Testing Frameworks

### Frameworks

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [mocha](https://github.com/mochajs/mocha) | [mochajs/mocha](https://github.com/mochajs/mocha) | Simple, flexible, fun JavaScript test framework for node.js & the browser. | ![GitHub](https://img.shields.io/github/stars/mochajs/mocha) |
| [jasmine](https://github.com/jasmine/jasmine) | [jasmine/jasmine](https://github.com/jasmine/jasmine) | DOM-less simple JavaScript testing framework. | ![GitHub](https://img.shields.io/github/stars/jasmine/jasmine) |
| [qunit](https://github.com/jquery/qunit) | [jquery/qunit](https://github.com/jquery/qunit) | An easy-to-use JavaScript Unit Testing framework. | ![GitHub](https://img.shields.io/github/stars/jquery/qunit) |
| [jest](https://github.com/facebook/jest) | [facebook/jest](https://github.com/facebook/jest) | Painless JavaScript Unit Testing. | ![GitHub](https://img.shields.io/github/stars/facebook/jest) |
| [prova](https://github.com/azer/prova) | [azer/prova](https://github.com/azer/prova) | Node & Browser test runner based on Tape and Browserify | ![GitHub](https://img.shields.io/github/stars/azer/prova) |
| [DalekJS](https://github.com/dalekjs/dalek) | [dalekjs/dalek](https://github.com/dalekjs/dalek) | Automated cross browser functional testing with JavaScript | ![GitHub](https://img.shields.io/github/stars/dalekjs/dalek) |
| [Protractor](https://github.com/angular/protractor) | [angular/protractor](https://github.com/angular/protractor) | Protractor is an end-to-end test framework for AngularJS applications. | ![GitHub](https://img.shields.io/github/stars/angular/protractor) |
| [tape](https://github.com/substack/tape) | [substack/tape](https://github.com/substack/tape) | Tap-producing test harness for node and browsers. | ![GitHub](https://img.shields.io/github/stars/substack/tape) |
| [TestCafe](https://github.com/DevExpress/testcafe) | [DevExpress/testcafe](https://github.com/DevExpress/testcafe) | Automated browser testing for the modern web development stack. | ![GitHub](https://img.shields.io/github/stars/DevExpress/testcafe) |
| [ava](https://github.com/avajs/ava) | [avajs/ava](https://github.com/avajs/ava) | 🚀 Futuristic JavaScript test runner | ![GitHub](https://img.shields.io/github/stars/avajs/ava) |
| [Cypress](https://www.cypress.io/) | - | Complete end-to-end testing framework for anything that runs in a browser and beyond. |  |
| [WebdriverI/O](https://webdriver.io/) | - | Next-gen browser and mobile automation test framework for Node.js |  |


### Assertion

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [chai](https://github.com/chaijs/chai) | [chaijs/chai](https://github.com/chaijs/chai) | BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework. | ![GitHub](https://img.shields.io/github/stars/chaijs/chai) |
| [Enzyme](https://airbnb.io/enzyme/index.html) | - | Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output. |  |
| [react testing library](https://github.com/kentcdodds/react-testing-library) | [kentcdodds/react-testing-library](https://github.com/kentcdodds/react-testing-library) | Simple and complete React DOM testing utilities that encourage good testing practices. | ![GitHub](https://img.shields.io/github/stars/kentcdodds/react-testing-library) |
| [Sinon.JS](https://github.com/sinonjs/sinon) | [sinonjs/sinon](https://github.com/sinonjs/sinon) | Test spies, stubs, and mocks for JavaScript. | ![GitHub](https://img.shields.io/github/stars/sinonjs/sinon) |
| [expect.js](https://github.com/Automattic/expect.js) | [Automattic/expect.js](https://github.com/Automattic/expect.js) | Minimalistic BDD-style assertions for Node.JS and the browser. | ![GitHub](https://img.shields.io/github/stars/Automattic/expect.js) |
| [proxyquire](https://github.com/thlorenz/proxyquire) | [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | Stub nodejs's require. | ![GitHub](https://img.shields.io/github/stars/thlorenz/proxyquire) |
| [Supertest](https://github.com/visionmedia/supertest) | [visionmedia/supertest](https://github.com/visionmedia/supertest) | A popular HTTP assertion library for testing REST APIs, often used with other testing frameworks like Mocha or Jest | ![GitHub](https://img.shields.io/github/stars/visionmedia/supertest) |


### Coverage

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [istanbul](https://github.com/gotwarlost/istanbul) | [gotwarlost/istanbul](https://github.com/gotwarlost/istanbul) | Yet another JS code coverage tool. | ![GitHub](https://img.shields.io/github/stars/gotwarlost/istanbul) |
| [blanket](https://github.com/alex-seville/blanket) | [alex-seville/blanket](https://github.com/alex-seville/blanket) | A simple code coverage library for JavaScript. Designed to be easy to install and use, for both browser and nodejs. | ![GitHub](https://img.shields.io/github/stars/alex-seville/blanket) |
| [JSCover](https://github.com/tntim96/JSCover) | [tntim96/JSCover](https://github.com/tntim96/JSCover) | JSCover is a tool that measures code coverage for JavaScript programs. | ![GitHub](https://img.shields.io/github/stars/tntim96/JSCover) |


### Runner

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [phantomjs](https://github.com/ariya/phantomjs) | [ariya/phantomjs](https://github.com/ariya/phantomjs) | Scriptable Headless WebKit. | ![GitHub](https://img.shields.io/github/stars/ariya/phantomjs) |
| [slimerjs](https://github.com/laurentj/slimerjs) | [laurentj/slimerjs](https://github.com/laurentj/slimerjs) | A PhantomJS-like tool running Gecko. | ![GitHub](https://img.shields.io/github/stars/laurentj/slimerjs) |
| [casperjs](https://github.com/casperjs/casperjs) | [casperjs/casperjs](https://github.com/casperjs/casperjs) | Navigation scripting & testing utility for PhantomJS and SlimerJS. | ![GitHub](https://img.shields.io/github/stars/casperjs/casperjs) |
| [zombie](https://github.com/assaf/zombie) | [assaf/zombie](https://github.com/assaf/zombie) | Insanely fast, full-stack, headless browser testing using node.js. | ![GitHub](https://img.shields.io/github/stars/assaf/zombie) |
| [totoro](https://github.com/totorojs/totoro) | [totorojs/totoro](https://github.com/totorojs/totoro) | A simple and stable cross-browser testing tool. | ![GitHub](https://img.shields.io/github/stars/totorojs/totoro) |
| [karma](https://github.com/karma-runner/karma) | [karma-runner/karma](https://github.com/karma-runner/karma) | Spectacular Test Runner for JavaScript. | ![GitHub](https://img.shields.io/github/stars/karma-runner/karma) |
| [nightwatch](https://github.com/nightwatchjs/nightwatch) | [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | UI automated testing framework based on node.js and selenium webdriver. | ![GitHub](https://img.shields.io/github/stars/nightwatchjs/nightwatch) |
| [intern](https://github.com/theintern/intern) | [theintern/intern](https://github.com/theintern/intern) | A next-generation code testing stack for JavaScript. | ![GitHub](https://img.shields.io/github/stars/theintern/intern) |
| [puppeteer](https://github.com/GoogleChrome/puppeteer) | [GoogleChrome/puppeteer](https://github.com/GoogleChrome/puppeteer) | Headless Chrome Node.js API by official Google Chrome team. | ![GitHub](https://img.shields.io/github/stars/GoogleChrome/puppeteer) |
| [webdriverio](https://github.com/webdriverio/webdriverio) | [webdriverio/webdriverio](https://github.com/webdriverio/webdriverio) | Next-gen WebDriver test automation framework for Node.js. | ![GitHub](https://img.shields.io/github/stars/webdriverio/webdriverio) |
| [taiko](https://github.com/getgauge/taiko) | [getgauge/taiko](https://github.com/getgauge/taiko) | A Node.js library with a simple API to automate Chromium based browsers. | ![GitHub](https://img.shields.io/github/stars/getgauge/taiko) |
| [Playwright](https://github.com/microsoft/playwright) | [microsoft/playwright](https://github.com/microsoft/playwright) | Node.js library to automate Chromium, Firefox and WebKit with a single API. | ![GitHub](https://img.shields.io/github/stars/microsoft/playwright) |


## QA Tools

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [prettier](https://github.com/prettier/prettier) | [prettier/prettier](https://github.com/prettier/prettier) | Prettier is an opinionated code formatter. | ![GitHub](https://img.shields.io/github/stars/prettier/prettier) |
| [JSHint](https://github.com/jshint/jshint/) | [jshint/jshint](https://github.com/jshint/jshint) | JSHint is a tool that helps to detect errors and potential problems in your JavaScript code. | ![GitHub](https://img.shields.io/github/stars/jshint/jshint) |
| [jscs](https://github.com/jscs-dev/node-jscs) | [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | JavaScript Code Style checker. | ![GitHub](https://img.shields.io/github/stars/jscs-dev/node-jscs) |
| [jsfmt](https://github.com/rdio/jsfmt) | [rdio/jsfmt](https://github.com/rdio/jsfmt) | For formatting, searching, and rewriting JavaScript. | ![GitHub](https://img.shields.io/github/stars/rdio/jsfmt) |
| [jsinspect](https://github.com/danielstjules/jsinspect) | [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | Detect copy-pasted and structurally similar code. | ![GitHub](https://img.shields.io/github/stars/danielstjules/jsinspect) |
| [buddy.js](https://github.com/danielstjules/buddy.js) | [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | Magic number detection for JavaScript. | ![GitHub](https://img.shields.io/github/stars/danielstjules/buddy.js) |
| [ESLint](https://github.com/eslint/eslint) | [eslint/eslint](https://github.com/eslint/eslint) | A fully pluggable tool for identifying and reporting on patterns in JavaScript. | ![GitHub](https://img.shields.io/github/stars/eslint/eslint) |
| [JSLint](https://github.com/douglascrockford/JSLint) | [douglascrockford/JSLint](https://github.com/douglascrockford/JSLint) | High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language. | ![GitHub](https://img.shields.io/github/stars/douglascrockford/JSLint) |
| [JavaScript Standard Style](https://github.com/feross/standard) | [feross/standard](https://github.com/feross/standard) | Opinionated, no-configuration style guide, style checker, and formatter | ![GitHub](https://img.shields.io/github/stars/feross/standard) |
| [Pre-evaluate code at buildtime](https://github.com/kentcdodds/preval.macro) | [kentcdodds/preval.macro](https://github.com/kentcdodds/preval.macro) | Pre-evaluate your front end javascript code at build-time | ![GitHub](https://img.shields.io/github/stars/kentcdodds/preval.macro) |
| [JS-Beautifier](https://github.com/beautify-web/js-beautify) | [beautify-web/js-beautify](https://github.com/beautify-web/js-beautify) | Npm cli and library to format JS code. | ![GitHub](https://img.shields.io/github/stars/beautify-web/js-beautify) |
| [husky](https://github.com/typicode/husky) | [typicode/husky](https://github.com/typicode/husky) | Prevents bad git commit, git push and more. | ![GitHub](https://img.shields.io/github/stars/typicode/husky) |


## MVC Frameworks and Libraries

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [angular.js](https://github.com/angular/angular.js) | [angular/angular.js](https://github.com/angular/angular.js) | HTML enhanced for web apps. (deprecated) | ![GitHub](https://img.shields.io/github/stars/angular/angular.js) |
| [angular](https://github.com/angular/angular) | [angular/angular](https://github.com/angular/angular) | Angular is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages. | ![GitHub](https://img.shields.io/github/stars/angular/angular) |
| [aurelia](http://aurelia.io) | - | A JavaScript client framework for mobile, desktop and web. |  |
| [backbone](https://github.com/jashkenas/backbone) | [jashkenas/backbone](https://github.com/jashkenas/backbone) | Give your JS App some Backbone with Models, Views, Collections, and Events. | ![GitHub](https://img.shields.io/github/stars/jashkenas/backbone) |
| [ember.js](https://github.com/emberjs/ember.js) | [emberjs/ember.js](https://github.com/emberjs/ember.js) | A JavaScript framework for creating ambitious web applications. | ![GitHub](https://img.shields.io/github/stars/emberjs/ember.js) |
| [meteor](https://github.com/meteor/meteor) | [meteor/meteor](https://github.com/meteor/meteor) | An ultra-simple, database-everywhere, data-on-the-wire, pure-javascript web framework. | ![GitHub](https://img.shields.io/github/stars/meteor/meteor) |
| [ractive](https://github.com/ractivejs/ractive) | [ractivejs/ractive](https://github.com/ractivejs/ractive) | Next-generation DOM manipulation. | ![GitHub](https://img.shields.io/github/stars/ractivejs/ractive) |
| [vue](https://github.com/vuejs/vue) | [vuejs/vue](https://github.com/vuejs/vue) | Intuitive, fast & composable MVVM for building interactive interfaces. | ![GitHub](https://img.shields.io/github/stars/vuejs/vue) |
| [svelte](https://github.com/sveltejs/svelte) | [sveltejs/svelte](https://github.com/sveltejs/svelte) | Svelte is a new way to build web applications. It's a compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM. | ![GitHub](https://img.shields.io/github/stars/sveltejs/svelte) |
| [knockout](https://github.com/knockout/knockout) | [knockout/knockout](https://github.com/knockout/knockout) | Knockout makes it easier to create rich, responsive UIs with JavaScript. | ![GitHub](https://img.shields.io/github/stars/knockout/knockout) |
| [spine](https://github.com/spine/spine) | [spine/spine](https://github.com/spine/spine) | Lightweight MVC library for building JavaScript applications. | ![GitHub](https://img.shields.io/github/stars/spine/spine) |
| [espresso.js](https://github.com/techlayer/espresso.js) | [techlayer/espresso.js](https://github.com/techlayer/espresso.js) | A minimal JavaScript library for crafting user interfaces. | ![GitHub](https://img.shields.io/github/stars/techlayer/espresso.js) |
| [canjs](https://github.com/canjs/canjs) | [canjs/canjs](https://github.com/canjs/canjs) | Can do JS, better, faster, easier. | ![GitHub](https://img.shields.io/github/stars/canjs/canjs) |
| [react](https://reactjs.org/) | - | A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM. |  |
| [hyperapp](https://github.com/hyperapp/hyperapp) | [hyperapp/hyperapp](https://github.com/hyperapp/hyperapp) | 1kb JavaScript library for building frontend applications. | ![GitHub](https://img.shields.io/github/stars/hyperapp/hyperapp) |
| [preact](https://github.com/developit/preact) | [developit/preact](https://github.com/developit/preact) | Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM. | ![GitHub](https://img.shields.io/github/stars/developit/preact) |
| [nativescript](https://github.com/NativeScript/NativeScript) | [NativeScript/NativeScript](https://github.com/NativeScript/NativeScript) | Build truly native cross-platform iOS and Android apps with JavaScript. | ![GitHub](https://img.shields.io/github/stars/NativeScript/NativeScript) |
| [react-native](https://github.com/facebook/react-native) | [facebook/react-native](https://github.com/facebook/react-native) | A framework for building native apps with React. | ![GitHub](https://img.shields.io/github/stars/facebook/react-native) |
| [riot](https://github.com/riot/riot) | [riot/riot](https://github.com/riot/riot) | React-like library, but with very small size. | ![GitHub](https://img.shields.io/github/stars/riot/riot) |
| [thorax](https://github.com/walmartlabs/thorax) | [walmartlabs/thorax](https://github.com/walmartlabs/thorax) | Strengthening your Backbone. | ![GitHub](https://img.shields.io/github/stars/walmartlabs/thorax) |
| [chaplin](https://github.com/chaplinjs/chaplin) | [chaplinjs/chaplin](https://github.com/chaplinjs/chaplin) | An architecture for JavaScript applications using the Backbone.js library. | ![GitHub](https://img.shields.io/github/stars/chaplinjs/chaplin) |
| [marionette](https://github.com/marionettejs/backbone.marionette) | [marionettejs/backbone.marionette](https://github.com/marionettejs/backbone.marionette) | A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications. | ![GitHub](https://img.shields.io/github/stars/marionettejs/backbone.marionette) |
| [ripple](https://github.com/ripplejs/ripple) | [ripplejs/ripple](https://github.com/ripplejs/ripple) | A tiny foundation for building reactive views. | ![GitHub](https://img.shields.io/github/stars/ripplejs/ripple) |
| [rivets](https://github.com/mikeric/rivets) | [mikeric/rivets](https://github.com/mikeric/rivets) | Lightweight and powerful data binding + templating solution. | ![GitHub](https://img.shields.io/github/stars/mikeric/rivets) |
| [derby](https://github.com/derbyjs/derby) | [derbyjs/derby](https://github.com/derbyjs/derby) | MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers. | ![GitHub](https://img.shields.io/github/stars/derbyjs/derby) |
| [derby-awesome](https://github.com/russll/awesome-derby) | [russll/awesome-derby](https://github.com/russll/awesome-derby) | A collection of awesome derby components | ![GitHub](https://img.shields.io/github/stars/russll/awesome-derby) |
| [way.js](https://github.com/gwendall/way.js) | [gwendall/way.js](https://github.com/gwendall/way.js) | Simple, lightweight, persistent two-way databinding. | ![GitHub](https://img.shields.io/github/stars/gwendall/way.js) |
| [mithril.js](https://github.com/lhorie/mithril.js) | [lhorie/mithril.js](https://github.com/lhorie/mithril.js) | Mithril is a client-side MVC framework (Light-weight, Robust, Fast). | ![GitHub](https://img.shields.io/github/stars/lhorie/mithril.js) |
| [jsblocks](https://github.com/astoilkov/jsblocks) | [astoilkov/jsblocks](https://github.com/astoilkov/jsblocks) | jsblocks is better MV-ish framework. | ![GitHub](https://img.shields.io/github/stars/astoilkov/jsblocks) |
| [feathers](https://github.com/feathersjs/feathers) | [feathersjs/feathers](https://github.com/feathersjs/feathers) | A minimalist real-time JavaScript framework for tomorrow's apps. | ![GitHub](https://img.shields.io/github/stars/feathersjs/feathers) |
| [Keo](https://github.com/Wildhoney/Keo) | [Wildhoney/Keo](https://github.com/Wildhoney/Keo) | Functional stateless React components with Shadow DOM support. | ![GitHub](https://img.shields.io/github/stars/Wildhoney/Keo) |
| [atvjs](https://github.com/emadalam/atvjs) | [emadalam/atvjs](https://github.com/emadalam/atvjs) | Blazing fast Apple TV application development using pure JavaScript. | ![GitHub](https://img.shields.io/github/stars/emadalam/atvjs) |
| [Alpine.js](https://github.com/alpinejs/alpine) | [alpinejs/alpine](https://github.com/alpinejs/alpine) | offers you the reactive and declarative nature of big frameworks like Vue or React at a much lower cost. | ![GitHub](https://img.shields.io/github/stars/alpinejs/alpine) |
| [inferno](https://github.com/infernojs/inferno) | [infernojs/inferno](https://github.com/infernojs/inferno) | 🔥 An extremely fast, React-like JavaScript library for building modern user interfaces. | ![GitHub](https://img.shields.io/github/stars/infernojs/inferno) |
| [FoalTS](https://foalts.org) | - | Elegant and all-inclusive Node.JS framework for building web applications (TypeScript). |  |
| [Lucia](https://github.com/aidenybai/lucia) | [aidenybai/lucia](https://github.com/aidenybai/lucia) | 3kb library for tiny web apps. | ![GitHub](https://img.shields.io/github/stars/aidenybai/lucia) |
| [Adonis](https://github.com/adonisjs/core) | [adonisjs/core](https://github.com/adonisjs/core) | The Node.js Framework highly focused on developer ergonomics, stability and confidence. | ![GitHub](https://img.shields.io/github/stars/adonisjs/core) |
| [GrapesJS](https://github.com/artf/grapesjs) | [artf/grapesjs](https://github.com/artf/grapesjs) | Free and Open source Web Builder Framework. Next generation tool for building templates without coding. | ![GitHub](https://img.shields.io/github/stars/artf/grapesjs) |
| [Rete.js](https://github.com/retejs/rete) | [retejs/rete](https://github.com/retejs/rete) | A modular framework for visual programming allows to create node based editor in browser. | ![GitHub](https://img.shields.io/github/stars/retejs/rete) |
| [litegraph.js](https://github.com/jagenjo/litegraph.js) | [jagenjo/litegraph.js](https://github.com/jagenjo/litegraph.js) | A graph node engine and editor similar to PD or UDK Blueprints, comes with its own editor in HTML5 Canvas2D. | ![GitHub](https://img.shields.io/github/stars/jagenjo/litegraph.js) |
| [Drawflow](https://github.com/jerosoler/Drawflow) | [jerosoler/Drawflow](https://github.com/jerosoler/Drawflow) | This allow you to create data flows easily and quickly. | ![GitHub](https://img.shields.io/github/stars/jerosoler/Drawflow) |
| [Blockly](https://github.com/google/blockly) | [google/blockly](https://github.com/google/blockly) | A library that adds a visual code editor to web and mobile apps by Google. | ![GitHub](https://img.shields.io/github/stars/google/blockly) |
| [Million](https://github.com/aidenybai/million) | [aidenybai/million](https://github.com/aidenybai/million) | <1kb compiler-focused virtual DOM. It's fast! | ![GitHub](https://img.shields.io/github/stars/aidenybai/million) |
| [Whatsup](https://github.com/whatsup/whatsup) | [whatsup/whatsup](https://github.com/whatsup/whatsup) | A frontend framework for chillout-mode development 🥤. JSX components on generators, fast mobx-like state management and exclusive cssx style system. | ![GitHub](https://img.shields.io/github/stars/whatsup/whatsup) |
| [Remult](https://github.com/remult/remult) | [remult/remult](https://github.com/remult/remult) | A CRUD framework for full-stack TypeScript. | ![GitHub](https://img.shields.io/github/stars/remult/remult) |


## Node-Powered CMS Frameworks

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [KeystoneJS](https://github.com/keystonejs/keystone) | [keystonejs/keystone](https://github.com/keystonejs/keystone) | powerful CMS and web app framework. | ![GitHub](https://img.shields.io/github/stars/keystonejs/keystone) |
| [Reaction Commerce](https://github.com/reactioncommerce/reaction) | [reactioncommerce/reaction](https://github.com/reactioncommerce/reaction) | reactive CMS, real-time architecture and design. | ![GitHub](https://img.shields.io/github/stars/reactioncommerce/reaction) |
| [Ghost](https://github.com/tryghost/Ghost) | [tryghost/Ghost](https://github.com/tryghost/Ghost) | simple, powerful publishing platform. | ![GitHub](https://img.shields.io/github/stars/tryghost/Ghost) |
| [Apostrophe](https://github.com/punkave/apostrophe) | [punkave/apostrophe](https://github.com/punkave/apostrophe) | CMS with content editing and essential services. | ![GitHub](https://img.shields.io/github/stars/punkave/apostrophe) |
| [We.js](https://github.com/wejs/we/) | [wejs/we](https://github.com/wejs/we) | framework for real time apps, sites or blogs. | ![GitHub](https://img.shields.io/github/stars/wejs/we) |
| [Hatch.js](https://github.com/inventures/hatchjs) | [inventures/hatchjs](https://github.com/inventures/hatchjs) | CMS platform with social features. | ![GitHub](https://img.shields.io/github/stars/inventures/hatchjs) |
| [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) | [xtremespb/taracotjs-generator](https://github.com/xtremespb/taracotjs-generator) | fast and minimalist CMS based on Node.js. | ![GitHub](https://img.shields.io/github/stars/xtremespb/taracotjs-generator) |
| [Nodizecms](https://github.com/nodize/nodizecms) | [nodize/nodizecms](https://github.com/nodize/nodizecms) | CMS for CoffeeScript lovers. | ![GitHub](https://img.shields.io/github/stars/nodize/nodizecms) |
| [Cody](https://github.com/jcoppieters/cody) | [jcoppieters/cody](https://github.com/jcoppieters/cody) | CMS with WSYWYG editor. | ![GitHub](https://img.shields.io/github/stars/jcoppieters/cody) |
| [PencilBlue](https://github.com/pencilblue/pencilblue/) | [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | CMS and blogging platform. | ![GitHub](https://img.shields.io/github/stars/pencilblue/pencilblue) |
| [Strapi](https://github.com/strapi/strapi) | [strapi/strapi](https://github.com/strapi/strapi) | Open source Node.js Headless CMS to easily build customisable APIs. | ![GitHub](https://img.shields.io/github/stars/strapi/strapi) |
| [Factor](https://github.com/fiction-com/factor) | [fiction-com/factor](https://github.com/fiction-com/factor) | The Javascript CMS | ![GitHub](https://img.shields.io/github/stars/fiction-com/factor) |


## Templating Engines
*Templating engines allow you to perform string interpolation.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [mustache.js](https://github.com/janl/mustache.js) | [janl/mustache.js](https://github.com/janl/mustache.js) | Minimal templating with {{mustaches}} in JavaScript. | ![GitHub](https://img.shields.io/github/stars/janl/mustache.js) |
| [handlebars.js](https://github.com/handlebars-lang/handlebars.js) | [handlebars-lang/handlebars.js](https://github.com/handlebars-lang/handlebars.js) | An extension to the Mustache templating language. | ![GitHub](https://img.shields.io/github/stars/handlebars-lang/handlebars.js) |
| [nunjucks](https://mozilla.github.io/nunjucks/) | - | A rich and powerful templating language for JavaScript from Mozilla. |  |
| [hogan.js](https://github.com/twitter/hogan.js) | [twitter/hogan.js](https://github.com/twitter/hogan.js) | A compiler for the Mustache templating language. | ![GitHub](https://img.shields.io/github/stars/twitter/hogan.js) |
| [doT](https://github.com/olado/doT) | [olado/doT](https://github.com/olado/doT) | The fastest + concise JavaScript template engine for nodejs and browsers. | ![GitHub](https://img.shields.io/github/stars/olado/doT) |
| [dustjs](https://github.com/linkedin/dustjs/) | [linkedin/dustjs](https://github.com/linkedin/dustjs) | Asynchronous templates for the browser and node.js. | ![GitHub](https://img.shields.io/github/stars/linkedin/dustjs) |
| [eco](https://github.com/sstephenson/eco/) | [sstephenson/eco](https://github.com/sstephenson/eco) | Embedded CoffeeScript templates. | ![GitHub](https://img.shields.io/github/stars/sstephenson/eco) |
| [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) | [blueimp/JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) | < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies. | ![GitHub](https://img.shields.io/github/stars/blueimp/JavaScript-Templates) |
| [t.js](https://github.com/jasonmoo/t.js) | [jasonmoo/t.js](https://github.com/jasonmoo/t.js) | A tiny JavaScript templating framework in ~400 bytes gzipped. | ![GitHub](https://img.shields.io/github/stars/jasonmoo/t.js) |
| [Pug](https://github.com/pugjs/pug) | [pugjs/pug](https://github.com/pugjs/pug) | Robust, elegant, feature rich template engine for nodejs. (formerly known as Jade) | ![GitHub](https://img.shields.io/github/stars/pugjs/pug) |
| [EJS](https://github.com/mde/ejs) | [mde/ejs](https://github.com/mde/ejs) | Effective JavaScript templating. | ![GitHub](https://img.shields.io/github/stars/mde/ejs) |
| [xtemplate](https://github.com/xtemplate/xtemplate) | [xtemplate/xtemplate](https://github.com/xtemplate/xtemplate) | eXtensible Template Engine lib for node and the browser | ![GitHub](https://img.shields.io/github/stars/xtemplate/xtemplate) |
| [marko](https://github.com/marko-js/marko) | [marko-js/marko](https://github.com/marko-js/marko) | A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output. | ![GitHub](https://img.shields.io/github/stars/marko-js/marko) |
| [swig](https://github.com/paularmstrong/swig) | [paularmstrong/swig](https://github.com/paularmstrong/swig) | (Archived) A simple, powerful, and extendable Node.js and browser-based JavaScript template engine. | ![GitHub](https://img.shields.io/github/stars/paularmstrong/swig) |
| [hmpl](https://hmpl-lang.dev) | - | Server-oriented customizable templating for JavaScript. |  |


## Game Engines
| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [A-Frame](https://aframe.io) | - | Make WebVR. |  |
| [Cocos](https://www.cocos.com) | - | Open Source Cross-Platform Game Development Framework. |  |
| [Impact](https://impactjs.com) | - | Impact - HTML5 Canvas & JavaScript Game Engine. |  |
| [GDevelop](https://gdevelop.io) | - | Free and Easy Game-Making App. |  |
| [Kaboom.js](https://kaboomjs.com) | - | A game programming library that helps you make games fast and fun. |  |
| [Matter.js](https://brm.io/matter-js) | - | A 2D rigid body JavaScript physics engine. |  |
| [melonJS](https://melonjs.org) | - | Open source HTML5 game engine that empowers developers and designers to focus on content. |  |
| [Phaser](https://phaser.io) | - | Phaser - A fast, fun and free open source HTML5 game framework. |  |
| [PixiJS](https://pixijs.com) | - | The HTML5 Creation Engine. |  |
| [PlayCanvas](https://playcanvas.com) | - | PlayCanvas WebGL Game Engine. |  |


## Articles and Posts

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-voc%C3%AA-deveria-conhecer-b70e94d1d706) | - | Article about concepts of JavaScript Functional. |  |
| [Multi-threading using web-workers](https://www.loginradius.com/blog/async/adding-multi-threading-to-javascript-using-web-workers/) | - | Web Workers: Adding Multi-threading to JavaScript |  |
| [this keyword in JavaScript](https://www.loginradius.com/blog/async/breaking-down-this-keyword-in-javascript/) | - | Breaking down the 'this' keyword in JavaScript |  |


## Data Visualization
*Data visualization tools for the web.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [d3](https://github.com/d3/d3) | [d3/d3](https://github.com/d3/d3) | A JavaScript visualization library for HTML and SVG. | ![GitHub](https://img.shields.io/github/stars/d3/d3) |
| [metrics-graphics](https://github.com/mozilla/metrics-graphics) | [mozilla/metrics-graphics](https://github.com/mozilla/metrics-graphics) | A library optimized for concise, principled data graphics and layouts. | ![GitHub](https://img.shields.io/github/stars/mozilla/metrics-graphics) |
| [three.js](https://github.com/mrdoob/three.js) | [mrdoob/three.js](https://github.com/mrdoob/three.js) | JavaScript 3D library. | ![GitHub](https://img.shields.io/github/stars/mrdoob/three.js) |
| [Chart.js](https://github.com/chartjs/Chart.js) | [chartjs/Chart.js](https://github.com/chartjs/Chart.js) | Simple HTML5 Charts using the &lt;canvas&gt; tag. | ![GitHub](https://img.shields.io/github/stars/chartjs/Chart.js) |
| [paper.js](https://github.com/paperjs/paper.js) | [paperjs/paper.js](https://github.com/paperjs/paper.js) | The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas. | ![GitHub](https://img.shields.io/github/stars/paperjs/paper.js) |
| [fabric.js](https://github.com/kangax/fabric.js) | [kangax/fabric.js](https://github.com/kangax/fabric.js) | JavaScript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser. | ![GitHub](https://img.shields.io/github/stars/kangax/fabric.js) |
| [peity](https://github.com/benpickles/peity) | [benpickles/peity](https://github.com/benpickles/peity) | Progressive <svg> bar, line and pie charts. | ![GitHub](https://img.shields.io/github/stars/benpickles/peity) |
| [raphael](https://github.com/DmitryBaranovskiy/raphael) | [DmitryBaranovskiy/raphael](https://github.com/DmitryBaranovskiy/raphael) | JavaScript Vector Library. | ![GitHub](https://img.shields.io/github/stars/DmitryBaranovskiy/raphael) |
| [echarts](https://github.com/apache/echarts) | [apache/echarts](https://github.com/apache/echarts) | Enterprise Charts. | ![GitHub](https://img.shields.io/github/stars/apache/echarts) |
| [visjs](https://github.com/visjs) | - | Multiple Libraries for dynamic, browser-based data visualization. |  |
| [two.js](https://github.com/jonobr1/two.js) | [jonobr1/two.js](https://github.com/jonobr1/two.js) | A renderer agnostic two-dimensional drawing api for the web. | ![GitHub](https://img.shields.io/github/stars/jonobr1/two.js) |
| [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) | [DmitryBaranovskiy/g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) | Charts for Raphaël. | ![GitHub](https://img.shields.io/github/stars/DmitryBaranovskiy/g.raphael) |
| [sigma.js](https://github.com/jacomyal/sigma.js) | [jacomyal/sigma.js](https://github.com/jacomyal/sigma.js) | A JavaScript library dedicated to graph drawing. | ![GitHub](https://img.shields.io/github/stars/jacomyal/sigma.js) |
| [arbor](https://github.com/samizdatco/arbor) | [samizdatco/arbor](https://github.com/samizdatco/arbor) | A graph visualization library using web workers and jQuery. | ![GitHub](https://img.shields.io/github/stars/samizdatco/arbor) |
| [cubism](https://github.com/square/cubism) | [square/cubism](https://github.com/square/cubism) | A D3 plugin for visualizing time series. | ![GitHub](https://img.shields.io/github/stars/square/cubism) |
| [dc.js](https://github.com/dc-js/dc.js) | [dc-js/dc.js](https://github.com/dc-js/dc.js) | Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js | ![GitHub](https://img.shields.io/github/stars/dc-js/dc.js) |
| [vega](https://github.com/trifacta/vega) | [trifacta/vega](https://github.com/trifacta/vega) | A visualization grammar. | ![GitHub](https://img.shields.io/github/stars/trifacta/vega) |
| [envisionjs](https://github.com/HumbleSoftware/envisionjs) | [HumbleSoftware/envisionjs](https://github.com/HumbleSoftware/envisionjs) | Dynamic HTML5 visualization. | ![GitHub](https://img.shields.io/github/stars/HumbleSoftware/envisionjs) |
| [rickshaw](https://github.com/shutterstock/rickshaw) | [shutterstock/rickshaw](https://github.com/shutterstock/rickshaw) | JavaScript toolkit for creating interactive real-time graphs. | ![GitHub](https://img.shields.io/github/stars/shutterstock/rickshaw) |
| [flot](https://github.com/flot/flot) | [flot/flot](https://github.com/flot/flot) | Attractive JavaScript charts for jQuery. | ![GitHub](https://img.shields.io/github/stars/flot/flot) |
| [morris.js](https://github.com/morrisjs/morris.js) | [morrisjs/morris.js](https://github.com/morrisjs/morris.js) | Pretty time-series line graphs. | ![GitHub](https://img.shields.io/github/stars/morrisjs/morris.js) |
| [nvd3](https://github.com/novus/nvd3) | [novus/nvd3](https://github.com/novus/nvd3) | Build re-usable charts and chart components for d3.js. | ![GitHub](https://img.shields.io/github/stars/novus/nvd3) |
| [svg.js](https://github.com/wout/svg.js) | [wout/svg.js](https://github.com/wout/svg.js) | A lightweight library for manipulating and animating SVG. | ![GitHub](https://img.shields.io/github/stars/wout/svg.js) |
| [heatmap.js](https://github.com/pa7/heatmap.js) | [pa7/heatmap.js](https://github.com/pa7/heatmap.js) | JavaScript Library for HTML5 canvas based heatmaps. | ![GitHub](https://img.shields.io/github/stars/pa7/heatmap.js) |
| [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) | [gwatts/jquery.sparkline](https://github.com/gwatts/jquery.sparkline) | A plugin for the jQuery JavaScript library to generate small sparkline charts directly in the browser. | ![GitHub](https://img.shields.io/github/stars/gwatts/jquery.sparkline) |
| [trianglify](https://github.com/qrohlf/trianglify) | [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | Low poly style background generator with d3.js. | ![GitHub](https://img.shields.io/github/stars/qrohlf/trianglify) |
| [d3-cloud](https://github.com/jasondavies/d3-cloud) | [jasondavies/d3-cloud](https://github.com/jasondavies/d3-cloud) | Create word clouds in JavaScript. | ![GitHub](https://img.shields.io/github/stars/jasondavies/d3-cloud) |
| [d4](https://github.com/heavysixer/d4) | [heavysixer/d4](https://github.com/heavysixer/d4) | A friendly reusable charts DSL for D3. | ![GitHub](https://img.shields.io/github/stars/heavysixer/d4) |
| [dimple.js](http://dimplejs.org) | - | Easy charts for business analytics powered by d3. |  |
| [chartist-js](https://github.com/gionkunz/chartist-js) | [gionkunz/chartist-js](https://github.com/gionkunz/chartist-js) | Simple responsive charts. | ![GitHub](https://img.shields.io/github/stars/gionkunz/chartist-js) |
| [epoch](https://github.com/epochjs/epoch) | [epochjs/epoch](https://github.com/epochjs/epoch) | A general purpose real-time charting library. | ![GitHub](https://img.shields.io/github/stars/epochjs/epoch) |
| [c3](https://github.com/c3js/c3) | [c3js/c3](https://github.com/c3js/c3) | D3-based reusable chart library. | ![GitHub](https://img.shields.io/github/stars/c3js/c3) |
| [BabylonJS](https://github.com/BabylonJS/Babylon.js) | [BabylonJS/Babylon.js](https://github.com/BabylonJS/Babylon.js) | A framework for building 3D games with HTML 5 and WebGL. | ![GitHub](https://img.shields.io/github/stars/BabylonJS/Babylon.js) |
| [recharts](https://github.com/recharts/recharts) | [recharts/recharts](https://github.com/recharts/recharts) | Redefined chart library built with React and D3. | ![GitHub](https://img.shields.io/github/stars/recharts/recharts) |
| [GraphicsJS](https://github.com/AnyChart/GraphicsJS) | [AnyChart/GraphicsJS](https://github.com/AnyChart/GraphicsJS) | A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology. | ![GitHub](https://img.shields.io/github/stars/AnyChart/GraphicsJS) |
| [mxGraph](https://github.com/jgraph/mxgraph) | [jgraph/mxgraph](https://github.com/jgraph/mxgraph) | Diagramming library that enables interactive graph and charting applications to be quickly created that run natively in any major browser that is supported by its vendor. | ![GitHub](https://img.shields.io/github/stars/jgraph/mxgraph) |
| [Frappe Charts](https://github.com/frappe/charts) | [frappe/charts](https://github.com/frappe/charts) | GitHub-inspired simple and modern SVG charts for the web with zero dependencies. | ![GitHub](https://img.shields.io/github/stars/frappe/charts) |
| [Frappe Gantt](https://github.com/frappe/gantt) | [frappe/gantt](https://github.com/frappe/gantt) | A simple, interactive, modern gantt chart library for the web. | ![GitHub](https://img.shields.io/github/stars/frappe/gantt) |
| [G2](https://github.com/antvis/G2) | [antvis/G2](https://github.com/antvis/G2) | A highly interactive data-driven visualization grammar for statistical charts. | ![GitHub](https://img.shields.io/github/stars/antvis/G2) |
| [G2Plot](https://github.com/antvis/G2Plot) | [antvis/G2Plot](https://github.com/antvis/G2Plot) | An interactive and responsive charting library. Based on the grammar of graphics. | ![GitHub](https://img.shields.io/github/stars/antvis/G2Plot) |
| [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) | [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | A fully featured graph theory library. | ![GitHub](https://img.shields.io/github/stars/cytoscape/cytoscape.js) |
| [cola.js](https://ialab.it.monash.edu/webcola/) | - | library for arranging your HTML5 documents and diagrams using constraint-based optimization techniques |  |
| [jointjs](https://github.com/clientIO/joint) | [clientIO/joint](https://github.com/clientIO/joint) | Diagramming library to create static diagrams or fully interactive diagramming tools. | ![GitHub](https://img.shields.io/github/stars/clientIO/joint) |
| [vizzu](https://github.com/vizzuhq/vizzu-lib) | [vizzuhq/vizzu-lib](https://github.com/vizzuhq/vizzu-lib) | Library for animated data visualizations and data stories. | ![GitHub](https://img.shields.io/github/stars/vizzuhq/vizzu-lib) |

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](https://www.anychart.com/), [plotly](https://plotly.com/), and [lightning chart](https://www.arction.com/lightningchart-js/).


## Timeline

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) | [NUKnightLab/TimelineJS3](https://github.com/NUKnightLab/TimelineJS3) | A Storytelling Timeline built in JavaScript. | ![GitHub](https://img.shields.io/github/stars/NUKnightLab/TimelineJS3) |
| [timesheet.js](https://github.com/sbstjn/timesheet.js) | [sbstjn/timesheet.js](https://github.com/sbstjn/timesheet.js) | JavaScript library for simple HTML5 & CSS3 time sheets. | ![GitHub](https://img.shields.io/github/stars/sbstjn/timesheet.js) |


## Spreadsheet

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [HANDSONTABLE](https://github.com/handsontable/handsontable) | [handsontable/handsontable](https://github.com/handsontable/handsontable) | Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers | ![GitHub](https://img.shields.io/github/stars/handsontable/handsontable) |
| [Frappe Datatable](https://github.com/frappe/datatable) | [frappe/datatable](https://github.com/frappe/datatable) | Frappe DataTable is a simple, modern and interactive datatable library for displaying tabular data. | ![GitHub](https://img.shields.io/github/stars/frappe/datatable) |
| [Luckysheet](https://github.com/mengshukeji/Luckysheet) | [mengshukeji/Luckysheet](https://github.com/mengshukeji/Luckysheet) | Luckysheet is an online spreadsheet like excel that is powerful, simple to configure, and completely open source. | ![GitHub](https://img.shields.io/github/stars/mengshukeji/Luckysheet) |
| [Jspreadsheet CE](https://github.com/jspreadsheet/ce) | [jspreadsheet/ce](https://github.com/jspreadsheet/ce) | Jspreadsheet is a lightweight vanilla javascript plugin to create amazing web-based interactive tables and spreadsheets compatible with other spreadsheet software. | ![GitHub](https://img.shields.io/github/stars/jspreadsheet/ce) |
| [RevoGrid](https://github.com/revolist/revogrid) | [revolist/revogrid](https://github.com/revolist/revogrid) | RevoGrid is a fast, responsive excel like data grid library for modern web applications. | ![GitHub](https://img.shields.io/github/stars/revolist/revogrid) |


## Editors

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [ace](https://github.com/ajaxorg/ace) | [ajaxorg/ace](https://github.com/ajaxorg/ace) | Ace (Ajax.org Cloud9 Editor). | ![GitHub](https://img.shields.io/github/stars/ajaxorg/ace) |
| [CodeMirror](https://github.com/codemirror/CodeMirror) | [codemirror/CodeMirror](https://github.com/codemirror/CodeMirror) | In-browser code editor. | ![GitHub](https://img.shields.io/github/stars/codemirror/CodeMirror) |
| [esprima](https://github.com/ariya/esprima) | [ariya/esprima](https://github.com/ariya/esprima) | ECMAScript parsing infrastructure for multipurpose analysis. | ![GitHub](https://img.shields.io/github/stars/ariya/esprima) |
| [quill](https://github.com/quilljs/quill) | [quilljs/quill](https://github.com/quilljs/quill) | A cross browser rich text editor with an API. | ![GitHub](https://img.shields.io/github/stars/quilljs/quill) |
| [medium-editor](https://github.com/yabwe/medium-editor) | [yabwe/medium-editor](https://github.com/yabwe/medium-editor) | Medium.com WYSIWYG editor clone. | ![GitHub](https://img.shields.io/github/stars/yabwe/medium-editor) |
| [pen](https://github.com/sofish/pen) | [sofish/pen](https://github.com/sofish/pen) | enjoy live editing (+markdown). | ![GitHub](https://img.shields.io/github/stars/sofish/pen) |
| [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) | [raphaelcruzeiro/jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) | A simple, clean and elegant text editor. Inspired by the awesomeness of Medium. | ![GitHub](https://img.shields.io/github/stars/raphaelcruzeiro/jquery-notebook) |
| [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) | [mindmup/bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) | Tiny bootstrap-compatible WYSIWYG rich text editor. | ![GitHub](https://img.shields.io/github/stars/mindmup/bootstrap-wysiwyg) |
| [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) | [ckeditor/ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) | The best web text editor for everyone. | ![GitHub](https://img.shields.io/github/stars/ckeditor/ckeditor-releases) |
| [editor](https://github.com/lepture/editor) | [lepture/editor](https://github.com/lepture/editor) | A markdown editor. still on development. | ![GitHub](https://img.shields.io/github/stars/lepture/editor) |
| [EpicEditor](https://github.com/OscarGodson/EpicEditor) | [OscarGodson/EpicEditor](https://github.com/OscarGodson/EpicEditor) | An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more. | ![GitHub](https://img.shields.io/github/stars/OscarGodson/EpicEditor) |
| [jsoneditor](https://github.com/josdejong/jsoneditor) | [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | A web-based tool to view, edit and format JSON. | ![GitHub](https://img.shields.io/github/stars/josdejong/jsoneditor) |
| [vim.js](https://github.com/coolwanglu/vim.js) | [coolwanglu/vim.js](https://github.com/coolwanglu/vim.js) | JavaScript port of Vim with a persistent `~/.vimrc`. | ![GitHub](https://img.shields.io/github/stars/coolwanglu/vim.js) |
| [Squire](https://github.com/neilj/Squire) | [neilj/Squire](https://github.com/neilj/Squire) | HTML5 rich text editor. | ![GitHub](https://img.shields.io/github/stars/neilj/Squire) |
| [TinyMCE](https://github.com/tinymce/tinymce) | [tinymce/tinymce](https://github.com/tinymce/tinymce) | The JavaScript Rich Text editor. | ![GitHub](https://img.shields.io/github/stars/tinymce/tinymce) |
| [trix](https://github.com/basecamp/trix) | [basecamp/trix](https://github.com/basecamp/trix) | A rich text editor for everyday writing. By Basecamp. | ![GitHub](https://img.shields.io/github/stars/basecamp/trix) |
| [Trumbowyg](https://github.com/Alex-D/Trumbowyg) | [Alex-D/Trumbowyg](https://github.com/Alex-D/Trumbowyg) | A lightweight and amazing WYSIWYG JavaScript editor. | ![GitHub](https://img.shields.io/github/stars/Alex-D/Trumbowyg) |
| [Draft.js](https://github.com/facebook/draft-js) | [facebook/draft-js](https://github.com/facebook/draft-js) | A React framework for building text editors. | ![GitHub](https://img.shields.io/github/stars/facebook/draft-js) |
| [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) | [jhollingworth/bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) | Simple, beautiful wysiwyg editor | ![GitHub](https://img.shields.io/github/stars/jhollingworth/bootstrap-wysihtml5) |
| [wysihtml5](https://github.com/xing/wysihtml5) | [xing/wysihtml5](https://github.com/xing/wysihtml5) | Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles. | ![GitHub](https://img.shields.io/github/stars/xing/wysihtml5) |
| [raptor-editor](https://github.com/PANmedia/raptor-editor) | [PANmedia/raptor-editor](https://github.com/PANmedia/raptor-editor) | Raptor, an HTML5 WYSIWYG content editor! | ![GitHub](https://img.shields.io/github/stars/PANmedia/raptor-editor) |
| [popline](https://github.com/kenshin54/popline) | [kenshin54/popline](https://github.com/kenshin54/popline) | Popline is an HTML5 Rich-Text-Editor Toolbar. | ![GitHub](https://img.shields.io/github/stars/kenshin54/popline) |
| [Summernote](https://github.com/summernote/summernote) | [summernote/summernote](https://github.com/summernote/summernote) | Super simple WYSIWYG editor. | ![GitHub](https://img.shields.io/github/stars/summernote/summernote) |
| [Everright-formEditor](https://github.com/Liberty-liu/Everright-formEditor) | [Liberty-liu/Everright-formEditor](https://github.com/Liberty-liu/Everright-formEditor) | A visual drag-and-drop low-code form editor | ![GitHub](https://img.shields.io/github/stars/Liberty-liu/Everright-formEditor) |


## Documentation

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [DevDocs](https://devdocs.io/) | - | is an all-in-one API documentation reader with a fast, organized, and consistent interface. |  |
| [docco](http://ashkenas.com/docco/) | - | is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator. |  |
| [styledocco](http://jacobrask.github.io/styledocco/) | - | generates documentation and style guide documents from your stylesheets. |  |
| [Ronn](https://github.com/rtomayko/ronn) | [rtomayko/ronn](https://github.com/rtomayko/ronn) | builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web. | ![GitHub](https://img.shields.io/github/stars/rtomayko/ronn) |
| [dox](https://github.com/tj/dox) | [tj/dox](https://github.com/tj/dox) | is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags. | ![GitHub](https://img.shields.io/github/stars/tj/dox) |
| [jsdox](https://github.com/sutoiku/jsdox) | [sutoiku/jsdox](https://github.com/sutoiku/jsdox) | is a JSDoc3 to Markdown documentation generator. | ![GitHub](https://img.shields.io/github/stars/sutoiku/jsdox) |
| [ESDoc](https://github.com/esdoc/esdoc) | [esdoc/esdoc](https://github.com/esdoc/esdoc) | is a good documentation generator for JavaScript. | ![GitHub](https://img.shields.io/github/stars/esdoc/esdoc) |
| [YUIDoc](http://yui.github.io/yuidoc/) | - | is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen. |  |
| [coddoc](http://doug-martin.github.io/coddoc/) | - | is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs. |  |
| [sphinx](http://www.sphinx-doc.org/) | - | a tool that makes it easy to create intelligent and beautiful documentation |  |
| [Beautiful docs](https://github.com/beautiful-docs/beautiful-docs) | [beautiful-docs/beautiful-docs](https://github.com/beautiful-docs/beautiful-docs) | is a documentation viewer based on markdown files. | ![GitHub](https://img.shields.io/github/stars/beautiful-docs/beautiful-docs) |
| [documentation.js](http://documentation.js.org) | - | API documentation generator with support for ES2015+ and flow annotation. |  |
| [jsduck](https://github.com/senchalabs/jsduck) | [senchalabs/jsduck](https://github.com/senchalabs/jsduck) | API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too. | ![GitHub](https://img.shields.io/github/stars/senchalabs/jsduck) |
| [codecrumbs](https://github.com/Bogdan-Lyashenko/codecrumbs) | [Bogdan-Lyashenko/codecrumbs](https://github.com/Bogdan-Lyashenko/codecrumbs) | is a visual tool for learning and documenting a codebase by putting breadcrumbs in source code. | ![GitHub](https://img.shields.io/github/stars/Bogdan-Lyashenko/codecrumbs) |


## Files
*Libraries for working with files.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Papa Parse](https://github.com/mholt/PapaParse) | [mholt/PapaParse](https://github.com/mholt/PapaParse) | A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV. | ![GitHub](https://img.shields.io/github/stars/mholt/PapaParse) |
| [jBinary](https://github.com/jDataView/jBinary) | [jDataView/jBinary](https://github.com/jDataView/jBinary) | High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures. | ![GitHub](https://img.shields.io/github/stars/jDataView/jBinary) |
| [diff2html](https://github.com/rtfpessoa/diff2html) | [rtfpessoa/diff2html](https://github.com/rtfpessoa/diff2html) | Git diff output parser and pretty HTML generator. | ![GitHub](https://img.shields.io/github/stars/rtfpessoa/diff2html) |
| [jsPDF](https://github.com/MrRio/jsPDF) | [MrRio/jsPDF](https://github.com/MrRio/jsPDF) | JavaScript PDF generation. | ![GitHub](https://img.shields.io/github/stars/MrRio/jsPDF) |
| [PDF.js](https://github.com/mozilla/pdf.js) | [mozilla/pdf.js](https://github.com/mozilla/pdf.js) | PDF Reader in JavaScript. | ![GitHub](https://img.shields.io/github/stars/mozilla/pdf.js) |


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [underscore](https://github.com/jashkenas/underscore) | [jashkenas/underscore](https://github.com/jashkenas/underscore) | JavaScript's utility _ belt. | ![GitHub](https://img.shields.io/github/stars/jashkenas/underscore) |
| [lodash](https://github.com/lodash/lodash) | [lodash/lodash](https://github.com/lodash/lodash) | A utility library delivering consistency, customization, performance, & extras. | ![GitHub](https://img.shields.io/github/stars/lodash/lodash) |
| [Sugar](https://github.com/andrewplummer/Sugar) | [andrewplummer/Sugar](https://github.com/andrewplummer/Sugar) | A JavaScript library for working with native objects. | ![GitHub](https://img.shields.io/github/stars/andrewplummer/Sugar) |
| [lazy.js](https://github.com/dtao/lazy.js) | [dtao/lazy.js](https://github.com/dtao/lazy.js) | Like Underscore, but lazier. | ![GitHub](https://img.shields.io/github/stars/dtao/lazy.js) |
| [ramda](https://github.com/ramda/ramda) | [ramda/ramda](https://github.com/ramda/ramda) | A practical functional library for JavaScript programmers. | ![GitHub](https://img.shields.io/github/stars/ramda/ramda) |
| [mout](https://github.com/mout/mout) | [mout/mout](https://github.com/mout/mout) | Modular JavaScript Utilities. | ![GitHub](https://img.shields.io/github/stars/mout/mout) |
| [preludejs](https://github.com/alanrsoares/prelude-js) | [alanrsoares/prelude-js](https://github.com/alanrsoares/prelude-js) | Hardcore Functional Programming for JavaScript. | ![GitHub](https://img.shields.io/github/stars/alanrsoares/prelude-js) |
| [rambda](https://github.com/selfrefactor/rambda) | [selfrefactor/rambda](https://github.com/selfrefactor/rambda) | Faster and smaller alternative to *Ramda*. | ![GitHub](https://img.shields.io/github/stars/selfrefactor/rambda) |
| [fxts](https://github.com/marpple/FxTS) | [marpple/FxTS](https://github.com/marpple/FxTS) | Lazy evaluation and concurrency. | ![GitHub](https://img.shields.io/github/stars/marpple/FxTS) |
| [wild-wild-path](https://github.com/ehmicky/wild-wild-path) | [ehmicky/wild-wild-path](https://github.com/ehmicky/wild-wild-path) | Object property paths with wildcards and regexps. | ![GitHub](https://img.shields.io/github/stars/ehmicky/wild-wild-path) |
| [sweet-monads](https://github.com/JSMonk/sweet-monads) | [JSMonk/sweet-monads](https://github.com/JSMonk/sweet-monads) | A utility library containing popular monads and lazy iterators. | ![GitHub](https://img.shields.io/github/stars/JSMonk/sweet-monads) |


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [RxJS](https://github.com/ReactiveX/rxjs) | [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | A reactive programming library for JavaScript. | ![GitHub](https://img.shields.io/github/stars/ReactiveX/rxjs) |
| [Bacon](https://github.com/baconjs/bacon.js) | [baconjs/bacon.js](https://github.com/baconjs/bacon.js) | FRP (functional reactive programming) library for JavaScript. | ![GitHub](https://img.shields.io/github/stars/baconjs/bacon.js) |
| [Kefir](https://github.com/pozadi/kefir) | [pozadi/kefir](https://github.com/pozadi/kefir) | FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption. | ![GitHub](https://img.shields.io/github/stars/pozadi/kefir) |
| [Highland](https://caolan.github.io/highland/) | - | Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams. |  |
| [Most.js](https://github.com/cujojs/most) | [cujojs/most](https://github.com/cujojs/most) | high performance FRP library. | ![GitHub](https://img.shields.io/github/stars/cujojs/most) |
| [MobX](https://github.com/mobxjs/mobx) | [mobxjs/mobx](https://github.com/mobxjs/mobx) | TFRP library for simple, scalable state management. | ![GitHub](https://img.shields.io/github/stars/mobxjs/mobx) |
| [Cycle.js](https://cycle.js.org) | - | A functional and reactive JavaScript library for cleaner code. |  |
| [concent](https://github.com/concentjs/concent) | [concentjs/concent](https://github.com/concentjs/concent) | Definitely the ❤️ simplest but ⚡️ strongest state management for react, it is predictable、progressive and efficient. | ![GitHub](https://img.shields.io/github/stars/concentjs/concent) |


## Data Structure
*Data structure libraries to build a more sophisticated application.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [immutable-js](https://github.com/facebook/immutable-js) | [facebook/immutable-js](https://github.com/facebook/immutable-js) | Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector. | ![GitHub](https://img.shields.io/github/stars/facebook/immutable-js) |
| [mori](https://github.com/swannodette/mori) | [swannodette/mori](https://github.com/swannodette/mori) | A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript. | ![GitHub](https://img.shields.io/github/stars/swannodette/mori) |
| [buckets](https://github.com/mauriciosantos/Buckets-JS) | [mauriciosantos/Buckets-JS](https://github.com/mauriciosantos/Buckets-JS) | A complete, fully tested and documented data structure library written in JavaScript. | ![GitHub](https://img.shields.io/github/stars/mauriciosantos/Buckets-JS) |
| [hashmap](https://github.com/flesler/hashmap) | [flesler/hashmap](https://github.com/flesler/hashmap) | Simple hashmap implementation that supports any kind of keys. | ![GitHub](https://img.shields.io/github/stars/flesler/hashmap) |
| [ngraph.graph](https://github.com/anvaka/ngraph.graph) | [anvaka/ngraph.graph](https://github.com/anvaka/ngraph.graph) | Graph data structure in javascript. | ![GitHub](https://img.shields.io/github/stars/anvaka/ngraph.graph) |
| [js-sdsl](https://github.com/zly201/js-sdsl) | [zly201/js-sdsl](https://github.com/zly201/js-sdsl) | Refer to the javascript standard data structure library implemented by c++ stl, which supports c++ bidirectional iterator mode. | ![GitHub](https://img.shields.io/github/stars/zly201/js-sdsl) |


## Date
*Date Libraries.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [moment](https://github.com/moment/moment) | [moment/moment](https://github.com/moment/moment) | Parse, validate, manipulate, and display dates in JavaScript. | ![GitHub](https://img.shields.io/github/stars/moment/moment) |
| [moment-timezone](https://github.com/moment/moment-timezone) | [moment/moment-timezone](https://github.com/moment/moment-timezone) | Timezone support for moment.js. | ![GitHub](https://img.shields.io/github/stars/moment/moment-timezone) |
| [jquery-timeago](https://github.com/rmm5t/jquery-timeago) | [rmm5t/jquery-timeago](https://github.com/rmm5t/jquery-timeago) | A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago"). | ![GitHub](https://img.shields.io/github/stars/rmm5t/jquery-timeago) |
| [timezone-js](https://github.com/mde/timezone-js) | [mde/timezone-js](https://github.com/mde/timezone-js) | Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data. | ![GitHub](https://img.shields.io/github/stars/mde/timezone-js) |
| [date](https://github.com/MatthewMueller/date) | [MatthewMueller/date](https://github.com/MatthewMueller/date) | Date() for humans. | ![GitHub](https://img.shields.io/github/stars/MatthewMueller/date) |
| [ms.js](https://github.com/rauchg/ms.js) | [rauchg/ms.js](https://github.com/rauchg/ms.js) | Tiny millisecond conversion utility. | ![GitHub](https://img.shields.io/github/stars/rauchg/ms.js) |
| [countdown.js](https://github.com/gumroad/countdown.js) | [gumroad/countdown.js](https://github.com/gumroad/countdown.js) | Super simple countdowns. | ![GitHub](https://img.shields.io/github/stars/gumroad/countdown.js) |
| [timeago.js](https://github.com/hustcc/timeago.js) | [hustcc/timeago.js](https://github.com/hustcc/timeago.js) | Simple library (less then 2kb) used to format date with `*** time ago` statement. | ![GitHub](https://img.shields.io/github/stars/hustcc/timeago.js) |
| [fecha](https://github.com/taylorhakes/fecha) | [taylorhakes/fecha](https://github.com/taylorhakes/fecha) | Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js. | ![GitHub](https://img.shields.io/github/stars/taylorhakes/fecha) |
| [date-fns](https://github.com/date-fns/date-fns) | [date-fns/date-fns](https://github.com/date-fns/date-fns) | Modern JavaScript date utility library. | ![GitHub](https://img.shields.io/github/stars/date-fns/date-fns) |
| [map-countdown](https://github.com/dawidjaniga/map-countdown) | [dawidjaniga/map-countdown](https://github.com/dawidjaniga/map-countdown) | A browser countdown built on top of the Google Maps. | ![GitHub](https://img.shields.io/github/stars/dawidjaniga/map-countdown) |
| [dayjs](https://github.com/iamkun/dayjs) | [iamkun/dayjs](https://github.com/iamkun/dayjs) | Day.js 2KB immutable date library alternative to Moment.js with the same modern API. | ![GitHub](https://img.shields.io/github/stars/iamkun/dayjs) |
| [luxon](https://github.com/moment/luxon) | [moment/luxon](https://github.com/moment/luxon) | Luxon is a library for working with dates and times in JavaScript. | ![GitHub](https://img.shields.io/github/stars/moment/luxon) |
| [tempo](https://github.com/formkit/tempo) | [formkit/tempo](https://github.com/formkit/tempo) | Parsing, formatting, and timezones — Tempo is a small tree-shakable library for native Date objects. | ![GitHub](https://img.shields.io/github/stars/formkit/tempo) |


## String
*String Libraries.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [voca](https://github.com/panzerdp/voca) | [panzerdp/voca](https://github.com/panzerdp/voca) | The ultimate JavaScript string library | ![GitHub](https://img.shields.io/github/stars/panzerdp/voca) |
| [selecting](https://github.com/EvandroLG/selecting) | [EvandroLG/selecting](https://github.com/EvandroLG/selecting) | A library that allows you to access the text selected by the user. | ![GitHub](https://img.shields.io/github/stars/EvandroLG/selecting) |
| [underscore.string](https://github.com/epeli/underscore.string) | [epeli/underscore.string](https://github.com/epeli/underscore.string) | String manipulation extensions for Underscore.js JavaScript library. | ![GitHub](https://img.shields.io/github/stars/epeli/underscore.string) |
| [string.js](https://github.com/jprichardson/string.js) | [jprichardson/string.js](https://github.com/jprichardson/string.js) | Extra JavaScript string methods. | ![GitHub](https://img.shields.io/github/stars/jprichardson/string.js) |
| [he](https://github.com/mathiasbynens/he) | [mathiasbynens/he](https://github.com/mathiasbynens/he) | A robust HTML entity encoder/decoder written in JavaScript. | ![GitHub](https://img.shields.io/github/stars/mathiasbynens/he) |
| [multiline](https://github.com/sindresorhus/multiline) | [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | Multiline strings in JavaScript. | ![GitHub](https://img.shields.io/github/stars/sindresorhus/multiline) |
| [query-string](https://github.com/sindresorhus/query-string) | [sindresorhus/query-string](https://github.com/sindresorhus/query-string) | Parse and stringify URL query strings. | ![GitHub](https://img.shields.io/github/stars/sindresorhus/query-string) |
| [URI.js](https://github.com/medialize/URI.js/) | [medialize/URI.js](https://github.com/medialize/URI.js) | JavaScript URL mutation library. | ![GitHub](https://img.shields.io/github/stars/medialize/URI.js) |
| [jsurl](https://github.com/Mikhus/domurl) | [Mikhus/domurl](https://github.com/Mikhus/domurl) | Lightweight URL manipulation with JavaScript. | ![GitHub](https://img.shields.io/github/stars/Mikhus/domurl) |
| [sprintf.js](https://github.com/alexei/sprintf.js) | [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | A sprintf implementation. | ![GitHub](https://img.shields.io/github/stars/alexei/sprintf.js) |
| [url-pattern](https://github.com/snd/url-pattern) | [snd/url-pattern](https://github.com/snd/url-pattern) | Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings. | ![GitHub](https://img.shields.io/github/stars/snd/url-pattern) |
| [plexis](https://github.com/plexis-js/plexis) | [plexis-js/plexis](https://github.com/plexis-js/plexis) | Lo-fi, powerful, community-driven string manipulation library. | ![GitHub](https://img.shields.io/github/stars/plexis-js/plexis) |
| [url-state-machine](https://github.com/anonrig/url-js) | [anonrig/url-js](https://github.com/anonrig/url-js) | Super fast spec-compliant URL parser state machine for Node.js. | ![GitHub](https://img.shields.io/github/stars/anonrig/url-js) |


## Number

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Numeral-js](https://github.com/adamwdraper/Numeral-js) | [adamwdraper/Numeral-js](https://github.com/adamwdraper/Numeral-js) | A JavaScript library for formatting and manipulating numbers. | ![GitHub](https://img.shields.io/github/stars/adamwdraper/Numeral-js) |
| [chance.js](https://github.com/chancejs/chancejs) | [chancejs/chancejs](https://github.com/chancejs/chancejs) | Random generator helper in JavaScript. Can generate numbers, strings etc. | ![GitHub](https://img.shields.io/github/stars/chancejs/chancejs) |
| [odometer](https://github.com/HubSpot/odometer) | [HubSpot/odometer](https://github.com/HubSpot/odometer) | Smoothly transitions numbers with ease. | ![GitHub](https://img.shields.io/github/stars/HubSpot/odometer) |
| [accounting.js](https://github.com/josscrowcroft/accounting.js) | [josscrowcroft/accounting.js](https://github.com/josscrowcroft/accounting.js) | A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies. | ![GitHub](https://img.shields.io/github/stars/josscrowcroft/accounting.js) |
| [money.js](https://github.com/josscrowcroft/money.js) | [josscrowcroft/money.js](https://github.com/josscrowcroft/money.js) | A tiny (1kb) JavaScript currency conversion library, for web & nodeJS. | ![GitHub](https://img.shields.io/github/stars/josscrowcroft/money.js) |
| [Fraction.js](https://github.com/infusion/Fraction.js) | [infusion/Fraction.js](https://github.com/infusion/Fraction.js) | A rational number library for JavaScript. | ![GitHub](https://img.shields.io/github/stars/infusion/Fraction.js) |
| [Complex.js](https://github.com/infusion/Complex.js) | [infusion/Complex.js](https://github.com/infusion/Complex.js) | A complex number library for JavaScript. | ![GitHub](https://img.shields.io/github/stars/infusion/Complex.js) |
| [Polynomial.js](https://github.com/infusion/Polynomial.js) | [infusion/Polynomial.js](https://github.com/infusion/Polynomial.js) | A polynomials library for JavaScript. | ![GitHub](https://img.shields.io/github/stars/infusion/Polynomial.js) |
| [Quaternion.js](https://github.com/infusion/Quaternion.js) | [infusion/Quaternion.js](https://github.com/infusion/Quaternion.js) | A quaternion library for JavaScript | ![GitHub](https://img.shields.io/github/stars/infusion/Quaternion.js) |


## Storage

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [store.js](https://github.com/marcuswestin/store.js) | [marcuswestin/store.js](https://github.com/marcuswestin/store.js) | LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood. | ![GitHub](https://img.shields.io/github/stars/marcuswestin/store.js) |
| [localForage](https://github.com/mozilla/localForage) | [mozilla/localForage](https://github.com/mozilla/localForage) | Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API. | ![GitHub](https://img.shields.io/github/stars/mozilla/localForage) |
| [jStorage](https://github.com/andris9/jStorage) | [andris9/jStorage](https://github.com/andris9/jStorage) | jStorage is a simple key/value database to store data on browser side. | ![GitHub](https://img.shields.io/github/stars/andris9/jStorage) |
| [cross-storage](https://github.com/zendesk/cross-storage) | [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | Cross domain local storage, with permissions. | ![GitHub](https://img.shields.io/github/stars/zendesk/cross-storage) |
| [basket.js](https://github.com/addyosmani/basket.js) | [addyosmani/basket.js](https://github.com/addyosmani/basket.js) | A script and resource loader for caching & loading scripts with localStorage. | ![GitHub](https://img.shields.io/github/stars/addyosmani/basket.js) |
| [bag.js](https://github.com/nodeca/bag.js) | [nodeca/bag.js](https://github.com/nodeca/bag.js) | A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support. | ![GitHub](https://img.shields.io/github/stars/nodeca/bag.js) |
| [basil.js](https://github.com/Wisembly/basil.js) | [Wisembly/basil.js](https://github.com/Wisembly/basil.js) | The missing JavaScript smart persistent layer. | ![GitHub](https://img.shields.io/github/stars/Wisembly/basil.js) |
| [jquery-cookie](https://github.com/carhartl/jquery-cookie) | [carhartl/jquery-cookie](https://github.com/carhartl/jquery-cookie) | A simple, lightweight jQuery plugin for reading, writing and deleting cookies. | ![GitHub](https://img.shields.io/github/stars/carhartl/jquery-cookie) |
| [js-cookie](https://github.com/js-cookie/js-cookie) | [js-cookie/js-cookie](https://github.com/js-cookie/js-cookie) | A simple, lightweight JavaScript API for handling browser cookies. | ![GitHub](https://img.shields.io/github/stars/js-cookie/js-cookie) |
| [Cookies](https://github.com/ScottHamper/Cookies) | [ScottHamper/Cookies](https://github.com/ScottHamper/Cookies) | JavaScript Client-Side Cookie Manipulation Library. | ![GitHub](https://img.shields.io/github/stars/ScottHamper/Cookies) |
| [DB.js](https://github.com/aaronpowell/db.js/) | [aaronpowell/db.js](https://github.com/aaronpowell/db.js) | Promise based IndexDB Wrapper library. | ![GitHub](https://img.shields.io/github/stars/aaronpowell/db.js) |
| [lawnchair.js](https://github.com/brianleroux/lawnchair/) | [brianleroux/lawnchair](https://github.com/brianleroux/lawnchair) | Simple client-side JSON storage. | ![GitHub](https://img.shields.io/github/stars/brianleroux/lawnchair) |
| [sql.js](https://github.com/kripken/sql.js) | [kripken/sql.js](https://github.com/kripken/sql.js) | SQLite compiled to JavaScript through Emscripten. | ![GitHub](https://img.shields.io/github/stars/kripken/sql.js) |
| [pouchdb](https://github.com/pouchdb/pouchdb) | [pouchdb/pouchdb](https://github.com/pouchdb/pouchdb) | Javascript db inspired by Apache CouchDB to run well within the browser. | ![GitHub](https://img.shields.io/github/stars/pouchdb/pouchdb) |
| [crumbsjs](https://github.com/nirtz89/crumbsjs) | [nirtz89/crumbsjs](https://github.com/nirtz89/crumbsjs) | A lightweight vanilla ES6 cookies and local storage JavaScript library. | ![GitHub](https://img.shields.io/github/stars/nirtz89/crumbsjs) |
| [awesome-web-storage](https://github.com/softvar/awesome-web-storage) | [softvar/awesome-web-storage](https://github.com/softvar/awesome-web-storage) | Everything you need to know about client-side storage. | ![GitHub](https://img.shields.io/github/stars/softvar/awesome-web-storage) |
| [datavore](https://github.com/StanfordHCI/datavore) | [StanfordHCI/datavore](https://github.com/StanfordHCI/datavore) | A small, fast, in-browser database engine written in JavaScript. | ![GitHub](https://img.shields.io/github/stars/StanfordHCI/datavore) |
| [Hoodie](https://github.com/hoodiehq/hoodie) | [hoodiehq/hoodie](https://github.com/hoodiehq/hoodie) | Offline First backend to work in browser without internet connectivity. | ![GitHub](https://img.shields.io/github/stars/hoodiehq/hoodie) |
| [NeDB](https://github.com/louischatriot/nedb) | [louischatriot/nedb](https://github.com/louischatriot/nedb) | Embedded Persistent database for Browsers, nw.js, electron. | ![GitHub](https://img.shields.io/github/stars/louischatriot/nedb) |
| [Lovefield](https://google.github.io/lovefield) | - | Lovefield is a relational database for web apps, By Google. |  |
| [Dexie.js](https://github.com/dexie/Dexie.js) | [dexie/Dexie.js](https://github.com/dexie/Dexie.js) | Dexie.js is a wrapper library for indexedDB. | ![GitHub](https://img.shields.io/github/stars/dexie/Dexie.js) |
| [proxy-web-storage](https://github.com/KID-joker/proxy-web-storage) | [KID-joker/proxy-web-storage](https://github.com/KID-joker/proxy-web-storage) | Keep the type of storage value unchanged and change array and object directly. Supports listening to the changes and setting expires. | ![GitHub](https://img.shields.io/github/stars/KID-joker/proxy-web-storage) |
| [PostgreSQL Browser](https://github.com/datawan-labs/pg) | [datawan-labs/pg](https://github.com/datawan-labs/pg) | Browser PostgreSQL Playground, no server, just client and pglite (postgresql wasm) | ![GitHub](https://img.shields.io/github/stars/datawan-labs/pg) |


## Color

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [randomColor](https://github.com/davidmerfield/randomColor) | [davidmerfield/randomColor](https://github.com/davidmerfield/randomColor) | A color generator for JavaScript. | ![GitHub](https://img.shields.io/github/stars/davidmerfield/randomColor) |
| [chroma.js](https://github.com/gka/chroma.js) | [gka/chroma.js](https://github.com/gka/chroma.js) | JavaScript library for all kinds of color manipulations. | ![GitHub](https://img.shields.io/github/stars/gka/chroma.js) |
| [color](https://github.com/Qix-/color) | [Qix-/color](https://github.com/Qix-/color) | JavaScript color conversion and manipulation library. | ![GitHub](https://img.shields.io/github/stars/Qix-/color) |
| [colors](https://github.com/mrmrs/colors) | [mrmrs/colors](https://github.com/mrmrs/colors) | Smarter defaults for colors on the web. | ![GitHub](https://img.shields.io/github/stars/mrmrs/colors) |
| [PleaseJS](https://github.com/Fooidge/PleaseJS) | [Fooidge/PleaseJS](https://github.com/Fooidge/PleaseJS) | JavaScript Library for creating random pleasing colors and color schemes. | ![GitHub](https://img.shields.io/github/stars/Fooidge/PleaseJS) |
| [TinyColor](https://github.com/bgrins/TinyColor) | [bgrins/TinyColor](https://github.com/bgrins/TinyColor) | Fast, small color manipulation and conversion for JavaScript. | ![GitHub](https://img.shields.io/github/stars/bgrins/TinyColor) |
| [Vibrant.js](https://github.com/jariz/vibrant.js/) | [jariz/vibrant.js](https://github.com/jariz/vibrant.js) | Extract prominent colors from an image. | ![GitHub](https://img.shields.io/github/stars/jariz/vibrant.js) |


## i18n and l10n
*Internationalization (i18n) and localization (l10n) JavaScript libraries.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [i18next](https://github.com/i18next/i18next) | [i18next/i18next](https://github.com/i18next/i18next) | internationalisation (i18n) with JavaScript the easy way. | ![GitHub](https://img.shields.io/github/stars/i18next/i18next) |
| [polyglot](https://github.com/airbnb/polyglot.js) | [airbnb/polyglot.js](https://github.com/airbnb/polyglot.js) | tiny i18n helper library. | ![GitHub](https://img.shields.io/github/stars/airbnb/polyglot.js) |
| [babelfish](https://github.com/nodeca/babelfish/) | [nodeca/babelfish](https://github.com/nodeca/babelfish) | i18n with human friendly API and built in plurals support. | ![GitHub](https://img.shields.io/github/stars/nodeca/babelfish) |
| [ttag](https://github.com/ttag-org/ttag) | [ttag-org/ttag](https://github.com/ttag-org/ttag) | Modern javascript i18n localization library based on ES6 tagged templates and the good old GNU gettext. | ![GitHub](https://img.shields.io/github/stars/ttag-org/ttag) |
| [attranslate](https://github.com/fkirc/attranslate) | [fkirc/attranslate](https://github.com/fkirc/attranslate) | A JavaScript-tool for synchronizing translation-files, including JSON/YAML/XML and other formats. | ![GitHub](https://img.shields.io/github/stars/fkirc/attranslate) |


## Control Flow

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [async](https://github.com/caolan/async) | [caolan/async](https://github.com/caolan/async) | Async utilities for node and the browser. | ![GitHub](https://img.shields.io/github/stars/caolan/async) |
| [q](https://github.com/kriskowal/q) | [kriskowal/q](https://github.com/kriskowal/q) | A tool for making and composing asynchronous promises in JavaScript. | ![GitHub](https://img.shields.io/github/stars/kriskowal/q) |
| [step](https://github.com/creationix/step/) | [creationix/step](https://github.com/creationix/step) | An async control-flow library that makes stepping through logic easy. | ![GitHub](https://img.shields.io/github/stars/creationix/step) |
| [contra](https://github.com/bevacqua/contra/) | [bevacqua/contra](https://github.com/bevacqua/contra) | Asynchronous flow control with a functional taste to it. | ![GitHub](https://img.shields.io/github/stars/bevacqua/contra) |
| [Bluebird](https://github.com/petkaantonov/bluebird/) | [petkaantonov/bluebird](https://github.com/petkaantonov/bluebird) | fully featured promise library with focus on innovative features and performance. | ![GitHub](https://img.shields.io/github/stars/petkaantonov/bluebird) |
| [when](https://github.com/cujojs/when) | [cujojs/when](https://github.com/cujojs/when) | A solid, fast Promises/A+ and when() implementation, plus other async goodies. | ![GitHub](https://img.shields.io/github/stars/cujojs/when) |
| [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) | [gartz/ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) | Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers). | ![GitHub](https://img.shields.io/github/stars/gartz/ObjectEventTarget) |
| [sporadic](https://github.com/marcoonroad/sporadic) | [marcoonroad/sporadic](https://github.com/marcoonroad/sporadic) | Composable concurrency abstractions (such as streams, coroutines and Go-like channels) on top of promises, for Node and browser engines. | ![GitHub](https://img.shields.io/github/stars/marcoonroad/sporadic) |


## Routing

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [director](https://github.com/flatiron/director) | [flatiron/director](https://github.com/flatiron/director) | A tiny and isomorphic URL router for JavaScript. | ![GitHub](https://img.shields.io/github/stars/flatiron/director) |
| [page.js](https://github.com/visionmedia/page.js) | [visionmedia/page.js](https://github.com/visionmedia/page.js) | Micro client-side router inspired by the Express router (~1200 bytes). | ![GitHub](https://img.shields.io/github/stars/visionmedia/page.js) |
| [pathjs](https://github.com/mtrpcic/pathjs) | [mtrpcic/pathjs](https://github.com/mtrpcic/pathjs) | Simple, lightweight routing for web browsers. | ![GitHub](https://img.shields.io/github/stars/mtrpcic/pathjs) |
| [crossroads](https://github.com/millermedeiros/crossroads.js) | [millermedeiros/crossroads.js](https://github.com/millermedeiros/crossroads.js) | JavaScript Routes. | ![GitHub](https://img.shields.io/github/stars/millermedeiros/crossroads.js) |
| [davis.js](https://github.com/olivernn/davis.js) | [olivernn/davis.js](https://github.com/olivernn/davis.js) | RESTful degradable JavaScript routing using pushState. | ![GitHub](https://img.shields.io/github/stars/olivernn/davis.js) |
| [navaid](https://github.com/lukeed/navaid) | [lukeed/navaid](https://github.com/lukeed/navaid) | A navigation aid (aka, router) for the browser in 850 bytes~! | ![GitHub](https://img.shields.io/github/stars/lukeed/navaid) |


## Security

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [DOMPurify](https://github.com/cure53/DOMPurify) | [cure53/DOMPurify](https://github.com/cure53/DOMPurify) | A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG. | ![GitHub](https://img.shields.io/github/stars/cure53/DOMPurify) |
| [js-xss](https://github.com/leizongmin/js-xss) | [leizongmin/js-xss](https://github.com/leizongmin/js-xss) | Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist. | ![GitHub](https://img.shields.io/github/stars/leizongmin/js-xss) |
| [xss-filters](https://github.com/yahoo/xss-filters) | [yahoo/xss-filters](https://github.com/yahoo/xss-filters) | Secure XSS Filters by Yahoo. | ![GitHub](https://img.shields.io/github/stars/yahoo/xss-filters) |
| [sanitize-html](https://github.com/apostrophecms/sanitize-html) | [apostrophecms/sanitize-html](https://github.com/apostrophecms/sanitize-html) | sanitize-html provides a simple HTML sanitizer with a clear API. | ![GitHub](https://img.shields.io/github/stars/apostrophecms/sanitize-html) |


## Log

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [log](https://github.com/adamschwartz/log) | [adamschwartz/log](https://github.com/adamschwartz/log) | Console.log with style. | ![GitHub](https://img.shields.io/github/stars/adamschwartz/log) |
| [Conzole](https://github.com/Oaxoa/Conzole) | [Oaxoa/Conzole](https://github.com/Oaxoa/Conzole) | A debug panel built in JavaScript that wraps JavaScript native console object methods and functionality in a panel displayed inside the page. | ![GitHub](https://img.shields.io/github/stars/Oaxoa/Conzole) |
| [console.log-wrapper](https://github.com/patik/console.log-wrapper) | [patik/console.log-wrapper](https://github.com/patik/console.log-wrapper) | Log to the console in any browser with clarity. | ![GitHub](https://img.shields.io/github/stars/patik/console.log-wrapper) |
| [loglevel](https://github.com/pimterry/loglevel) | [pimterry/loglevel](https://github.com/pimterry/loglevel) | Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods. | ![GitHub](https://img.shields.io/github/stars/pimterry/loglevel) |
| [minilog](http://mixu.net/minilog/) | - | – Lightweight client & server-side logging with Stream-API backends. |  |
| [storyboard](http://guigrpa.github.io/storyboard/) | - | Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place. |  |
| [LogTape](https://logtape.org/) | - | Simple logging library with zero dependencies for Deno, Node.js, Bun, browsers, and edge functions. |  |


## RegExp

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [RegEx101](https://regex101.com/#javascript) | - | Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE. |  |
| [RegExr](https://regexr.com/) | - | HTML/JS based tool for creating, testing, and learning about Regular Expressions. |  |
| [Regulex](https://jex.im/regulex/) | - | JavaScript Regular Expression Parser & Visualizer. |  |
| [Regex-Vis](https://regex-vis.com/) | - | Regex visualizer & editor. |  |


## Voice Command

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [annyang](https://github.com/TalAter/annyang) | [TalAter/annyang](https://github.com/TalAter/annyang) | A JavaScript library for adding voice commands to your site, using speech recognition. | ![GitHub](https://img.shields.io/github/stars/TalAter/annyang) |
| [voix.js](https://github.com/pazguille/voix) | [pazguille/voix](https://github.com/pazguille/voix) | A JavaScript library to add voice commands to your sites, apps or games. | ![GitHub](https://img.shields.io/github/stars/pazguille/voix) |


## API

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [axios](https://github.com/axios/axios) | [axios/axios](https://github.com/axios/axios) | Promise based HTTP client for the browser and node.js. | ![GitHub](https://img.shields.io/github/stars/axios/axios) |
| [bottleneck](https://github.com/SGrondin/bottleneck) | [SGrondin/bottleneck](https://github.com/SGrondin/bottleneck) | A powerful rate limiter that makes throttling easy. | ![GitHub](https://img.shields.io/github/stars/SGrondin/bottleneck) |
| [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) | [bettiolo/oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) | JavaScript OAuth 1.0a signature generator for node and the browser. | ![GitHub](https://img.shields.io/github/stars/bettiolo/oauth-signature-js) |
| [amygdala](https://github.com/lincolnloop/amygdala) | [lincolnloop/amygdala](https://github.com/lincolnloop/amygdala) | RESTful HTTP client for JavaScript powered web applications. | ![GitHub](https://img.shields.io/github/stars/lincolnloop/amygdala) |
| [jquery.rest](https://github.com/jpillora/jquery.rest) | [jpillora/jquery.rest](https://github.com/jpillora/jquery.rest) | A jQuery plugin for easy consumption of RESTful APIs. | ![GitHub](https://img.shields.io/github/stars/jpillora/jquery.rest) |
| [Rails Ranger](https://github.com/victor-am/rails-ranger) | [victor-am/rails-ranger](https://github.com/victor-am/rails-ranger) | An opinionated REST client for Ruby on Rails APIs. | ![GitHub](https://img.shields.io/github/stars/victor-am/rails-ranger) |
| [wretch](https://github.com/elbywan/wretch) | [elbywan/wretch](https://github.com/elbywan/wretch) | A tiny wrapper built around fetch with an intuitive syntax. | ![GitHub](https://img.shields.io/github/stars/elbywan/wretch) |
| [FarFetch](https://github.com/WebsiteBeaver/far-fetch) | [WebsiteBeaver/far-fetch](https://github.com/WebsiteBeaver/far-fetch) | Modern Fetch API wrapper for simplicity, with concise file uploading. | ![GitHub](https://img.shields.io/github/stars/WebsiteBeaver/far-fetch) |
| [Optic](https://github.com/opticdev/optic) | [opticdev/optic](https://github.com/opticdev/optic) | Optic automatically documents and tests your APIs. | ![GitHub](https://img.shields.io/github/stars/opticdev/optic) |
| [SWR](https://github.com/vercel/swr) | [vercel/swr](https://github.com/vercel/swr) | React Hooks library for remote data fetching. | ![GitHub](https://img.shields.io/github/stars/vercel/swr) |
| [React Query](https://github.com/tannerlinsley/react-query) | [tannerlinsley/react-query](https://github.com/tannerlinsley/react-query) | Hooks for fetching, caching and updating asynchronous data in React. | ![GitHub](https://img.shields.io/github/stars/tannerlinsley/react-query) |
| [SWRV](https://github.com/Kong/swrv) | [Kong/swrv](https://github.com/Kong/swrv) | Stale-while-revalidate data fetching for Vue. | ![GitHub](https://img.shields.io/github/stars/Kong/swrv) |
| [Vue Query](https://github.com/DamianOsipiuk/vue-query) | [DamianOsipiuk/vue-query](https://github.com/DamianOsipiuk/vue-query) | Hooks for fetching, caching and updating asynchronous data in Vue. | ![GitHub](https://img.shields.io/github/stars/DamianOsipiuk/vue-query) |


## Streaming

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Tailor](https://github.com/zalando/tailor) | [zalando/tailor](https://github.com/zalando/tailor) | Streaming layout service for front-end microservices, inspired by Facebook's BigPipe. | ![GitHub](https://img.shields.io/github/stars/zalando/tailor) |


## Vision Detection

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [tracking.js](https://github.com/eduardolundgren/tracking.js) | [eduardolundgren/tracking.js](https://github.com/eduardolundgren/tracking.js) | A modern approach for Computer Vision on the web. | ![GitHub](https://img.shields.io/github/stars/eduardolundgren/tracking.js) |
| [ocrad.js](https://github.com/antimatter15/ocrad.js) | [antimatter15/ocrad.js](https://github.com/antimatter15/ocrad.js) | OCR in JavaScript via Emscripten. | ![GitHub](https://img.shields.io/github/stars/antimatter15/ocrad.js) |


## Machine Learning

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [ConvNetJS](https://github.com/karpathy/convnetjs) | [karpathy/convnetjs](https://github.com/karpathy/convnetjs) | Deep Learning in JavaScript. Train Convolutional Neural Networks (or ordinary ones) in your browser. | ![GitHub](https://img.shields.io/github/stars/karpathy/convnetjs) |
| [DN2A](https://github.com/dn2a/dn2a-javascript) | [dn2a/dn2a-javascript](https://github.com/dn2a/dn2a-javascript) | Digital Neural Networks Architecture. | ![GitHub](https://img.shields.io/github/stars/dn2a/dn2a-javascript) |
| [Brain.js](https://github.com/harthur/brain) | [harthur/brain](https://github.com/harthur/brain) | Neural networks in JavaScript. | ![GitHub](https://img.shields.io/github/stars/harthur/brain) |
| [Mind.js](https://github.com/stevenmiller888/mind) | [stevenmiller888/mind](https://github.com/stevenmiller888/mind) | A flexible neural network library. | ![GitHub](https://img.shields.io/github/stars/stevenmiller888/mind) |
| [Synaptic.js](https://github.com/cazala/synaptic) | [cazala/synaptic](https://github.com/cazala/synaptic) | Architecture-free neural network library for node.js and the browser. | ![GitHub](https://img.shields.io/github/stars/cazala/synaptic) |
| [TensorFlow.js](https://www.tensorflow.org/js/) | - | A JavaScript library for training and deploying ML models in the browser and on Node.js. |  |
| [ml5.js](https://ml5js.org) | - | Friendly Machine Learning for the Web. |  |
| [Synapses](https://github.com/mrdimosthenis/Synapses) | [mrdimosthenis/Synapses](https://github.com/mrdimosthenis/Synapses) | Lightweight cross-platform Neural Network library. | ![GitHub](https://img.shields.io/github/stars/mrdimosthenis/Synapses) |
| [m2cgen](https://github.com/BayesWitnesses/m2cgen) | [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) | A CLI tool to transpile trained classic ML models into a native JavaScript code with zero dependencies. | ![GitHub](https://img.shields.io/github/stars/BayesWitnesses/m2cgen) |
| [JS-PyTorch](https://github.com/eduardoleao052/js-pytorch) | [eduardoleao052/js-pytorch](https://github.com/eduardoleao052/js-pytorch) | GPU accelerated PyTorch in JavaScript. | ![GitHub](https://img.shields.io/github/stars/eduardoleao052/js-pytorch) |


## Browser Detection

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [bowser](https://github.com/ded/bowser) | [ded/bowser](https://github.com/ded/bowser) | a browser detector. | ![GitHub](https://img.shields.io/github/stars/ded/bowser) |


## Operating System

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [os.js](https://github.com/os-js/OS.js) | [os-js/OS.js](https://github.com/os-js/OS.js) | An open-source web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more. | ![GitHub](https://img.shields.io/github/stars/os-js/OS.js) |


## Benchmark

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [benchmark.js](https://github.com/bestiejs/benchmark.js) | [bestiejs/benchmark.js](https://github.com/bestiejs/benchmark.js) | A benchmarking library. As used on jsPerf.com. | ![GitHub](https://img.shields.io/github/stars/bestiejs/benchmark.js) |
| [matcha](https://github.com/logicalparadox/matcha) | [logicalparadox/matcha](https://github.com/logicalparadox/matcha) | A caffeine driven, simplistic approach to benchmarking. | ![GitHub](https://img.shields.io/github/stars/logicalparadox/matcha) |
| [bencher](https://github.com/bencherdev/bencher) | [bencherdev/bencher](https://github.com/bencherdev/bencher) | A suite of continuous benchmarking tools designed to catch performance regressions in CI. | ![GitHub](https://img.shields.io/github/stars/bencherdev/bencher) |


## Web Worker

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [partytown](https://github.com/BuilderIO/partytown) | [BuilderIO/partytown](https://github.com/BuilderIO/partytown) | Relocate resource intensive third-party scripts off of the main thread and into a web worker. | ![GitHub](https://img.shields.io/github/stars/BuilderIO/partytown) |
| [comlink](https://github.com/GoogleChromeLabs/comlink) | [GoogleChromeLabs/comlink](https://github.com/GoogleChromeLabs/comlink) | Comlink is a tiny library (1.1kB), that removes the mental barrier of thinking about postMessage and hides the fact that you are working with workers. | ![GitHub](https://img.shields.io/github/stars/GoogleChromeLabs/comlink) |
| [greenlet](https://github.com/developit/greenlet) | [developit/greenlet](https://github.com/developit/greenlet) | Move an async function into its own thread. | ![GitHub](https://img.shields.io/github/stars/developit/greenlet) |
| [workerize](https://github.com/developit/workerize) | [developit/workerize](https://github.com/developit/workerize) | Moves a module into a Web Worker, automatically reflecting exported functions as asynchronous proxies. | ![GitHub](https://img.shields.io/github/stars/developit/workerize) |
| [worker-dom](https://github.com/ampproject/worker-dom) | [ampproject/worker-dom](https://github.com/ampproject/worker-dom) | An in-progress implementation of the DOM API intended to run within a Web Worker. | ![GitHub](https://img.shields.io/github/stars/ampproject/worker-dom) |
| [threads.js](https://github.com/andywer/threads.js) | [andywer/threads.js](https://github.com/andywer/threads.js) | Offload CPU-intensive tasks to worker threads in node.js, web browsers and electron using one uniform API. | ![GitHub](https://img.shields.io/github/stars/andywer/threads.js) |
| [workly](https://github.com/pshihn/workly) | [pshihn/workly](https://github.com/pshihn/workly) | A really simple way to move a function or class to a web worker. | ![GitHub](https://img.shields.io/github/stars/pshihn/workly) |
| [stockroom](https://github.com/developit/stockroom) | [developit/stockroom](https://github.com/developit/stockroom) | Offload your store management to a worker easily. | ![GitHub](https://img.shields.io/github/stars/developit/stockroom) |
| [workerpool](https://github.com/josdejong/workerpool) | [josdejong/workerpool](https://github.com/josdejong/workerpool) | Offload tasks to a pool of workers on node.js and in the browser. | ![GitHub](https://img.shields.io/github/stars/josdejong/workerpool) |
| [clooney](https://github.com/GoogleChromeLabs/clooney) | [GoogleChromeLabs/clooney](https://github.com/GoogleChromeLabs/clooney) | Clooney is an actor library for the web. Use workers without thinking about workers. | ![GitHub](https://img.shields.io/github/stars/GoogleChromeLabs/clooney) |


## Code highlighting

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Highlight.js](https://github.com/isagalaev/highlight.js) | [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | JavaScript syntax highlighter. | ![GitHub](https://img.shields.io/github/stars/isagalaev/highlight.js) |
| [PrismJS](https://github.com/PrismJS/prism) | [PrismJS/prism](https://github.com/PrismJS/prism) | Lightweight, robust, elegant syntax highlighting. | ![GitHub](https://img.shields.io/github/stars/PrismJS/prism) |


## Loading Status
*Libraries for indicate load status.*

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Mprogress.js](https://github.com/lightningtgc/MProgress.js) | [lightningtgc/MProgress.js](https://github.com/lightningtgc/MProgress.js) | Create Google Material Design progress linear bars. | ![GitHub](https://img.shields.io/github/stars/lightningtgc/MProgress.js) |
| [NProgress](https://ricostacruz.com/nprogress/) | - | Slim progress bars for Ajax'y applications. |  |
| [Spin.js](https://github.com/fgnass/spin.js) | [fgnass/spin.js](https://github.com/fgnass/spin.js) | A spinning activity indicator. | ![GitHub](https://img.shields.io/github/stars/fgnass/spin.js) |
| [progress.js](https://github.com/usablica/progress.js) | [usablica/progress.js](https://github.com/usablica/progress.js) | Create and manage progress bar for every objects on the page. | ![GitHub](https://img.shields.io/github/stars/usablica/progress.js) |
| [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) | [kimmobrunfeldt/progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) | Beautiful and responsive progress bars with animated SVG paths. | ![GitHub](https://img.shields.io/github/stars/kimmobrunfeldt/progressbar.js) |
| [pace](https://github.com/HubSpot/pace) | [HubSpot/pace](https://github.com/HubSpot/pace) | Automatically add a progress bar to your site. | ![GitHub](https://img.shields.io/github/stars/HubSpot/pace) |
| [topbar](https://github.com/buunguyen/topbar) | [buunguyen/topbar](https://github.com/buunguyen/topbar) | Tiny & beautiful site-wide progress indicator. | ![GitHub](https://img.shields.io/github/stars/buunguyen/topbar) |
| [nanobar](https://github.com/jacoborus/nanobar) | [jacoborus/nanobar](https://github.com/jacoborus/nanobar) | Very lightweight progress bars. No jQuery. | ![GitHub](https://img.shields.io/github/stars/jacoborus/nanobar) |
| [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) | [codrops/PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) | Modern ways of revealing new content using SVG animations. | ![GitHub](https://img.shields.io/github/stars/codrops/PageLoadingEffects) |
| [SpinKit](https://github.com/tobiasahlin/SpinKit) | [tobiasahlin/SpinKit](https://github.com/tobiasahlin/SpinKit) | A collection of loading indicators animated with CSS. | ![GitHub](https://img.shields.io/github/stars/tobiasahlin/SpinKit) |
| [Ladda](https://github.com/hakimel/Ladda) | [hakimel/Ladda](https://github.com/hakimel/Ladda) | Buttons with built-in loading indicators. | ![GitHub](https://img.shields.io/github/stars/hakimel/Ladda) |
| [css-loaders](https://github.com/lukehaas/css-loaders) | [lukehaas/css-loaders](https://github.com/lukehaas/css-loaders) | A collection of loading spinners animated with CSS | ![GitHub](https://img.shields.io/github/stars/lukehaas/css-loaders) |


## Validation

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Parsley.js](https://github.com/guillaumepotier/Parsley.js) | [guillaumepotier/Parsley.js](https://github.com/guillaumepotier/Parsley.js) | Validate your forms, frontend, without writing a single line of JavaScript. | ![GitHub](https://img.shields.io/github/stars/guillaumepotier/Parsley.js) |
| [jquery-validation](https://github.com/jzaefferer/jquery-validation) | [jzaefferer/jquery-validation](https://github.com/jzaefferer/jquery-validation) | jQuery Validation Plugin. | ![GitHub](https://img.shields.io/github/stars/jzaefferer/jquery-validation) |
| [validator.js](https://github.com/chriso/validator.js) | [chriso/validator.js](https://github.com/chriso/validator.js) | String validation and sanitization. | ![GitHub](https://img.shields.io/github/stars/chriso/validator.js) |
| [validate.js](https://github.com/rickharrison/validate.js) | [rickharrison/validate.js](https://github.com/rickharrison/validate.js) | Lightweight JavaScript form validation library inspired by CodeIgniter. | ![GitHub](https://img.shields.io/github/stars/rickharrison/validate.js) |
| [validatr](https://github.com/jaymorrow/validatr/) | [jaymorrow/validatr](https://github.com/jaymorrow/validatr) | Cross Browser HTML5 Form Validation. | ![GitHub](https://img.shields.io/github/stars/jaymorrow/validatr) |
| [FormValidation](https://formvalidation.io/) | - | The best jQuery plugin to validate form fields. Formerly BootstrapValidator. |  |
| [is.js](https://github.com/arasatasaygin/is.js) | [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | Check types, regexps, presence, time and more. | ![GitHub](https://img.shields.io/github/stars/arasatasaygin/is.js) |
| [FieldVal](https://github.com/FieldVal/fieldval-js) | [FieldVal/fieldval-js](https://github.com/FieldVal/fieldval-js) | multipurpose validation library. Supports both sync and async validation. | ![GitHub](https://img.shields.io/github/stars/FieldVal/fieldval-js) |
| [Funval](https://github.com/neuledge/funval) | [neuledge/funval](https://github.com/neuledge/funval) | Data validation using functions interfaces (support TypeScript). | ![GitHub](https://img.shields.io/github/stars/neuledge/funval) |
| [vest](https://github.com/ealush/vest) | [ealush/vest](https://github.com/ealush/vest) | 🦺 Declarative form validation framework inspired by unit testing. | ![GitHub](https://img.shields.io/github/stars/ealush/vest) |


## Keyboard Wrappers

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [mousetrap](https://github.com/ccampbell/mousetrap) | [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | Simple library for handling keyboard shortcuts in JavaScript. | ![GitHub](https://img.shields.io/github/stars/ccampbell/mousetrap) |
| [keymaster](https://github.com/madrobby/keymaster) | [madrobby/keymaster](https://github.com/madrobby/keymaster) | A simple micro-library for defining and dispatching keyboard shortcuts. | ![GitHub](https://img.shields.io/github/stars/madrobby/keymaster) |
| [Keypress](https://github.com/dmauro/Keypress) | [dmauro/Keypress](https://github.com/dmauro/Keypress) | A keyboard input capturing utility in which any key can be a modifier key. | ![GitHub](https://img.shields.io/github/stars/dmauro/Keypress) |
| [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts. | ![GitHub](https://img.shields.io/github/stars/RobertWHurst/KeyboardJS) |
| [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) | [jeresig/jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) | jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination. | ![GitHub](https://img.shields.io/github/stars/jeresig/jquery.hotkeys) |
| [jwerty](https://github.com/keithamus/jwerty) | [keithamus/jwerty](https://github.com/keithamus/jwerty) | Awesome handling of keyboard events. | ![GitHub](https://img.shields.io/github/stars/keithamus/jwerty) |


## Tours And Guides

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [intro.js](https://github.com/usablica/intro.js) | [usablica/intro.js](https://github.com/usablica/intro.js) | A better way for new feature introduction and step-by-step users guide for your website and project. | ![GitHub](https://img.shields.io/github/stars/usablica/intro.js) |
| [shepherd](https://github.com/HubSpot/shepherd) | [HubSpot/shepherd](https://github.com/HubSpot/shepherd) | Guide your users through a tour of your app. | ![GitHub](https://img.shields.io/github/stars/HubSpot/shepherd) |
| [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) | [sorich87/bootstrap-tour](https://github.com/sorich87/bootstrap-tour) | Quick and easy product tours with Twitter Bootstrap Popovers. | ![GitHub](https://img.shields.io/github/stars/sorich87/bootstrap-tour) |
| [tourist](https://github.com/easelinc/tourist) | [easelinc/tourist](https://github.com/easelinc/tourist) | Simple, flexible tours for your app. | ![GitHub](https://img.shields.io/github/stars/easelinc/tourist) |
| [hopscotch](https://github.com/linkedin/hopscotch) | [linkedin/hopscotch](https://github.com/linkedin/hopscotch) | A framework to make it easy for developers to add product tours to their pages. | ![GitHub](https://img.shields.io/github/stars/linkedin/hopscotch) |
| [joyride](https://github.com/zurb/joyride) | [zurb/joyride](https://github.com/zurb/joyride) | jQuery feature tour plugin. | ![GitHub](https://img.shields.io/github/stars/zurb/joyride) |
| [focusable](https://github.com/zzarcon/focusable) | [zzarcon/focusable](https://github.com/zzarcon/focusable) | Set a spotlight focus on DOM element adding a overlay layer to the rest of the page. | ![GitHub](https://img.shields.io/github/stars/zzarcon/focusable) |
| [driver.js](https://github.com/kamranahmedse/driver.js) | [kamranahmedse/driver.js](https://github.com/kamranahmedse/driver.js) | Powerful yet light-weight, vanilla JavaScript engine to drive the user's focus across the page | ![GitHub](https://img.shields.io/github/stars/kamranahmedse/driver.js) |


## Notifications

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [iziToast](https://github.com/dolce/iziToast) | [dolce/iziToast](https://github.com/dolce/iziToast) | Elegant, responsive, flexible and lightweight notification plugin with no dependencies. | ![GitHub](https://img.shields.io/github/stars/dolce/iziToast) |
| [messenger](https://github.com/HubSpot/messenger) | [HubSpot/messenger](https://github.com/HubSpot/messenger) | Growl-style alerts and messages for your app. | ![GitHub](https://img.shields.io/github/stars/HubSpot/messenger) |
| [noty](https://github.com/needim/noty) | [needim/noty](https://github.com/needim/noty) | jQuery notification plugin. | ![GitHub](https://img.shields.io/github/stars/needim/noty) |
| [pnotify](https://github.com/sciactive/pnotify) | [sciactive/pnotify](https://github.com/sciactive/pnotify) | JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft. | ![GitHub](https://img.shields.io/github/stars/sciactive/pnotify) |
| [toastr](https://github.com/CodeSeven/toastr) | [CodeSeven/toastr](https://github.com/CodeSeven/toastr) | Simple JavaScript toast notifications. | ![GitHub](https://img.shields.io/github/stars/CodeSeven/toastr) |
| [humane-js](https://github.com/wavded/humane-js) | [wavded/humane-js](https://github.com/wavded/humane-js) | A simple, modern, browser notification system. | ![GitHub](https://img.shields.io/github/stars/wavded/humane-js) |
| [smoke.js](https://github.com/hxgf/smoke.js) | [hxgf/smoke.js](https://github.com/hxgf/smoke.js) | Framework-agnostic styled alert system for JavaScript. | ![GitHub](https://img.shields.io/github/stars/hxgf/smoke.js) |
| [notie](https://github.com/jaredreich/notie) | [jaredreich/notie](https://github.com/jaredreich/notie) | Simple notifications and inputs with no dependencies. | ![GitHub](https://img.shields.io/github/stars/jaredreich/notie) |
| [notifire](https://github.com/notifirehq/notifire) | [notifirehq/notifire](https://github.com/notifirehq/notifire) | Open-source notification infrastructure for products. | ![GitHub](https://img.shields.io/github/stars/notifirehq/notifire) |
| [toastify-js](https://github.com/apvarun/toastify-js) | [apvarun/toastify-js](https://github.com/apvarun/toastify-js) | Pure JavaScript library for better notification messages. | ![GitHub](https://img.shields.io/github/stars/apvarun/toastify-js) |


## Sliders

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Swiper](https://github.com/nolimits4web/Swiper) | [nolimits4web/Swiper](https://github.com/nolimits4web/Swiper) | Mobile touch slider and framework with hardware accelerated transitions. | ![GitHub](https://img.shields.io/github/stars/nolimits4web/Swiper) |
| [slick](https://github.com/kenwheeler/slick) | [kenwheeler/slick](https://github.com/kenwheeler/slick) | The last carousel you'll ever need. | ![GitHub](https://img.shields.io/github/stars/kenwheeler/slick) |
| [slidesJs](http://www.slidesjs.com) | - | Is a responsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions |  |
| [FlexSlider](https://github.com/woothemes/FlexSlider) | [woothemes/FlexSlider](https://github.com/woothemes/FlexSlider) | An awesome, fully responsive jQuery slider plugin. | ![GitHub](https://img.shields.io/github/stars/woothemes/FlexSlider) |
| [sly](https://github.com/darsain/sly) | [darsain/sly](https://github.com/darsain/sly) | JavaScript library for one-directional scrolling with item based navigation support. | ![GitHub](https://img.shields.io/github/stars/darsain/sly) |
| [vegas](https://github.com/jaysalvat/vegas) | [jaysalvat/vegas](https://github.com/jaysalvat/vegas) | A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows. | ![GitHub](https://img.shields.io/github/stars/jaysalvat/vegas) |
| [Sequence](https://github.com/IanLunn/Sequence) | [IanLunn/Sequence](https://github.com/IanLunn/Sequence) | CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications. | ![GitHub](https://img.shields.io/github/stars/IanLunn/Sequence) |
| [reveal.js](https://github.com/hakimel/reveal.js) | [hakimel/reveal.js](https://github.com/hakimel/reveal.js) | A framework for easily creating beautiful presentations using HTML. | ![GitHub](https://img.shields.io/github/stars/hakimel/reveal.js) |
| [impress.js](https://github.com/impress/impress.js) | [impress/impress.js](https://github.com/impress/impress.js) | It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com. | ![GitHub](https://img.shields.io/github/stars/impress/impress.js) |
| [bespoke.js](https://github.com/bespokejs/bespoke) | [bespokejs/bespoke](https://github.com/bespokejs/bespoke) | DIY Presentation Micro-Framework | ![GitHub](https://img.shields.io/github/stars/bespokejs/bespoke) |
| [Strut](https://github.com/tantaman/Strut) | [tantaman/Strut](https://github.com/tantaman/Strut) | Strut - An Impress.js and Bespoke.js Presentation Editor | ![GitHub](https://img.shields.io/github/stars/tantaman/Strut) |
| [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) | [dimsemenov/PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) | JavaScript image gallery for mobile and desktop, modular, framework independent. | ![GitHub](https://img.shields.io/github/stars/dimsemenov/PhotoSwipe) |
| [jcSlider](https://github.com/JoanClaret/jcSlider) | [JoanClaret/jcSlider](https://github.com/JoanClaret/jcSlider) | A responsive slider jQuery plugin with CSS animations. | ![GitHub](https://img.shields.io/github/stars/JoanClaret/jcSlider) |
| [basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) | [jcobb/basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) | Simple to use, simple to theme, simple to customise. | ![GitHub](https://img.shields.io/github/stars/jcobb/basic-jquery-slider) |
| [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) | [creative-punch/jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider) | A jQuery plugin for a slider with adaptive colored figcaption and navigation. | ![GitHub](https://img.shields.io/github/stars/creative-punch/jQuery.adaptive-slider) |
| [slidr](https://github.com/bchanx/slidr) | [bchanx/slidr](https://github.com/bchanx/slidr) | add some slide effects. | ![GitHub](https://img.shields.io/github/stars/bchanx/slidr) |
| [Flickity](https://github.com/metafizzy/flickity) | [metafizzy/flickity](https://github.com/metafizzy/flickity) | Touch, responsive, flickable galleries. | ![GitHub](https://img.shields.io/github/stars/metafizzy/flickity) |
| [Glide.js](https://github.com/jedrzejchalubek/glidejs) | [jedrzejchalubek/glidejs](https://github.com/jedrzejchalubek/glidejs) | Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast. | ![GitHub](https://img.shields.io/github/stars/jedrzejchalubek/glidejs) |
| [Embla Carousel](https://github.com/davidcetinkaya/embla-carousel) | [davidcetinkaya/embla-carousel](https://github.com/davidcetinkaya/embla-carousel) | An extensible low level carousel for the web, written in TypeScript. | ![GitHub](https://img.shields.io/github/stars/davidcetinkaya/embla-carousel) |

## Range Sliders

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) | [IonDen/ion.rangeSlider](https://github.com/IonDen/ion.rangeSlider) | Powerful and easily customizable range slider with many options and skin support. | ![GitHub](https://img.shields.io/github/stars/IonDen/ion.rangeSlider) |
| [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) | [ghusse/jQRangeSlider](https://github.com/ghusse/jQRangeSlider) | A JavaScript slider selector that supports dates. | ![GitHub](https://img.shields.io/github/stars/ghusse/jQRangeSlider) |
| [noUiSlider](https://github.com/leongersen/noUiSlider) | [leongersen/noUiSlider](https://github.com/leongersen/noUiSlider) | A lightweight, highly customizable range slider without bloat. | ![GitHub](https://img.shields.io/github/stars/leongersen/noUiSlider) |
| [rangeslider.js](https://github.com/andreruffert/rangeslider.js) | [andreruffert/rangeslider.js](https://github.com/andreruffert/rangeslider.js) | HTML5 input range slider element polyfill. | ![GitHub](https://img.shields.io/github/stars/andreruffert/rangeslider.js) |


## Form Widgets

### Input

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [typeahead.js](https://github.com/twitter/typeahead.js) | [twitter/typeahead.js](https://github.com/twitter/typeahead.js) | A fast and fully-featured autocomplete library. | ![GitHub](https://img.shields.io/github/stars/twitter/typeahead.js) |
| [tag-it](https://github.com/aehlke/tag-it) | [aehlke/tag-it](https://github.com/aehlke/tag-it) | A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete. | ![GitHub](https://img.shields.io/github/stars/aehlke/tag-it) |
| [At.js](https://github.com/ichord/At.js) | [ichord/At.js](https://github.com/ichord/At.js) | Add GitHub like mentions autocomplete to your application. | ![GitHub](https://img.shields.io/github/stars/ichord/At.js) |
| [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) | [jamesallardice/Placeholders.js](https://github.com/jamesallardice/Placeholders.js) | A JavaScript polyfill for the HTML5 placeholder attribute. | ![GitHub](https://img.shields.io/github/stars/jamesallardice/Placeholders.js) |
| [fancyInput](https://github.com/yairEO/fancyInput) | [yairEO/fancyInput](https://github.com/yairEO/fancyInput) | Makes typing in input fields fun with CSS3 effects. | ![GitHub](https://img.shields.io/github/stars/yairEO/fancyInput) |
| [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) | [xoxco/jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) | Magically convert a simple text input into a cool tag list with this jQuery plugin. | ![GitHub](https://img.shields.io/github/stars/xoxco/jQuery-Tags-Input) |
| [vanilla-masker](https://github.com/BankFacil/vanilla-masker) | [BankFacil/vanilla-masker](https://github.com/BankFacil/vanilla-masker) | A pure JavaScript mask input. | ![GitHub](https://img.shields.io/github/stars/BankFacil/vanilla-masker) |
| [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) | [IonDen/ion.checkRadio](https://github.com/IonDen/ion.checkRadio) | jQuery plugin for styling checkboxes and radio-buttons. With skin support. | ![GitHub](https://img.shields.io/github/stars/IonDen/ion.checkRadio) |
| [awesomplete](https://github.com/LeaVerou/awesomplete) | [LeaVerou/awesomplete](https://github.com/LeaVerou/awesomplete) | Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - https://projects.verou.me/awesomplete/ | ![GitHub](https://img.shields.io/github/stars/LeaVerou/awesomplete) |


### Calendar

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [pickadate.js](https://github.com/amsul/pickadate.js) | [amsul/pickadate.js](https://github.com/amsul/pickadate.js) | The mobile-friendly, responsive, and lightweight jQuery date & time input picker. | ![GitHub](https://img.shields.io/github/stars/amsul/pickadate.js) |
| [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) | [eternicode/bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) | A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode. | ![GitHub](https://img.shields.io/github/stars/eternicode/bootstrap-datepicker) |
| [Pikaday](https://github.com/dbushell/Pikaday) | [dbushell/Pikaday](https://github.com/dbushell/Pikaday) | A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS. | ![GitHub](https://img.shields.io/github/stars/dbushell/Pikaday) |
| [fullcalendar](https://github.com/fullcalendar/fullcalendar) | [fullcalendar/fullcalendar](https://github.com/fullcalendar/fullcalendar) | Full-sized drag & drop event calendar (jQuery plugin). | ![GitHub](https://img.shields.io/github/stars/fullcalendar/fullcalendar) |
| [rome](https://github.com/bevacqua/rome) | [bevacqua/rome](https://github.com/bevacqua/rome) | A customizable date (and time) picker. Dependency free, opt-in UI. | ![GitHub](https://img.shields.io/github/stars/bevacqua/rome) |
| [Date Range Picker](https://github.com/dangrossman/daterangepicker) | [dangrossman/daterangepicker](https://github.com/dangrossman/daterangepicker) | creates a dropdown menu from which a user can select a range of dates. | ![GitHub](https://img.shields.io/github/stars/dangrossman/daterangepicker) |
| [Duet Date Picker](https://github.com/duetds/date-picker) | [duetds/date-picker](https://github.com/duetds/date-picker) | open source version of Duet Design System’s accessible date picker, WCAG 2.1 accessibility complaint | ![GitHub](https://img.shields.io/github/stars/duetds/date-picker) |
| [tui.calendar](https://github.com/nhn/tui.calendar) | [nhn/tui.calendar](https://github.com/nhn/tui.calendar) | A JavaScript schedule calendar that is full featured. Now your service just got the customizable calendar. | ![GitHub](https://img.shields.io/github/stars/nhn/tui.calendar) |
| [Schedule-X](https://github.com/schedule-x/schedule-x) | [schedule-x/schedule-x](https://github.com/schedule-x/schedule-x) | Material design event calendar. Features drag & drop, dark mode, multiple views and more. | ![GitHub](https://img.shields.io/github/stars/schedule-x/schedule-x) |


### Select

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [selectize.js](https://github.com/selectize/selectize.js) | [selectize/selectize.js](https://github.com/selectize/selectize.js) | Selectize is the hybrid of a textbox and `<select>` box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc. | ![GitHub](https://img.shields.io/github/stars/selectize/selectize.js) |
| [select2](https://github.com/select2/select2) | [select2/select2](https://github.com/select2/select2) | a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results. | ![GitHub](https://img.shields.io/github/stars/select2/select2) |
| [chosen](https://github.com/harvesthq/chosen) | [harvesthq/chosen](https://github.com/harvesthq/chosen) | A library for making long, unwieldy select boxes more friendly. | ![GitHub](https://img.shields.io/github/stars/harvesthq/chosen) |


### File Uploader

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) | [blueimp/jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) | File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery. | ![GitHub](https://img.shields.io/github/stars/blueimp/jQuery-File-Upload) |
| [dropzone](https://github.com/enyo/dropzone) | [enyo/dropzone](https://github.com/enyo/dropzone) | Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars. | ![GitHub](https://img.shields.io/github/stars/enyo/dropzone) |
| [flow.js](https://github.com/flowjs/flow.js) | [flowjs/flow.js](https://github.com/flowjs/flow.js) | A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API. | ![GitHub](https://img.shields.io/github/stars/flowjs/flow.js) |
| [fine-uploader](https://github.com/FineUploader/fine-uploader) | [FineUploader/fine-uploader](https://github.com/FineUploader/fine-uploader) | Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading. | ![GitHub](https://img.shields.io/github/stars/FineUploader/fine-uploader) |
| [FileAPI](https://github.com/mailru/FileAPI) | [mailru/FileAPI](https://github.com/mailru/FileAPI) | A set of JavaScript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF. | ![GitHub](https://img.shields.io/github/stars/mailru/FileAPI) |
| [plupload](https://github.com/moxiecode/plupload) | [moxiecode/plupload](https://github.com/moxiecode/plupload) | A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash. | ![GitHub](https://img.shields.io/github/stars/moxiecode/plupload) |
| [filepond](https://github.com/pqina/filepond) | [pqina/filepond](https://github.com/pqina/filepond) | A JavaScript library that can upload anything you throw at it, optimizes images for faster uploads, and offers a great, accessible, silky smooth user experience. | ![GitHub](https://img.shields.io/github/stars/pqina/filepond) |


### Other

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [form](https://github.com/jquery-form/form) | [jquery-form/form](https://github.com/jquery-form/form) | jQuery Form Plugin. | ![GitHub](https://img.shields.io/github/stars/jquery-form/form) |
| [Garlic.js](https://github.com/guillaumepotier/Garlic.js) | [guillaumepotier/Garlic.js](https://github.com/guillaumepotier/Garlic.js) | Automatically persist your forms' text and select field values locally, until the form is submitted. | ![GitHub](https://img.shields.io/github/stars/guillaumepotier/Garlic.js) |
| [Countable](https://github.com/RadLikeWhoa/Countable) | [RadLikeWhoa/Countable](https://github.com/RadLikeWhoa/Countable) | A JavaScript function to add live paragraph-, word- and character-counting to an HTML element. | ![GitHub](https://img.shields.io/github/stars/RadLikeWhoa/Countable) |
| [card](https://github.com/jessepollak/card) | [jessepollak/card](https://github.com/jessepollak/card) | Make your credit card form better in one line of code. | ![GitHub](https://img.shields.io/github/stars/jessepollak/card) |
| [stretchy](https://github.com/LeaVerou/stretchy) | [LeaVerou/stretchy](https://github.com/LeaVerou/stretchy) | Form element autosizing, the way it should be. | ![GitHub](https://img.shields.io/github/stars/LeaVerou/stretchy) |
| [analytics](https://github.com/davidwells/analytics) | [davidwells/analytics](https://github.com/davidwells/analytics) | A lightweight, extendable analytics library designed to work with any third-party analytics provider to track page views, custom events, & identify users. | ![GitHub](https://img.shields.io/github/stars/davidwells/analytics) |
| [dat.GUI](https://github.com/dataarts/dat.gui) | [dataarts/dat.gui](https://github.com/dataarts/dat.gui) | A lightweight gui controller for changing variables in JavaScript. | ![GitHub](https://img.shields.io/github/stars/dataarts/dat.gui) |


## Tips

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [tipsy](https://github.com/jaz303/tipsy) | [jaz303/tipsy](https://github.com/jaz303/tipsy) | Facebook-style tooltips plugin for jQuery. | ![GitHub](https://img.shields.io/github/stars/jaz303/tipsy) |
| [opentip](https://github.com/enyo/opentip) | [enyo/opentip](https://github.com/enyo/opentip) | An open source JavaScript tooltip based on the prototype framework. | ![GitHub](https://img.shields.io/github/stars/enyo/opentip) |
| [qTip2](https://github.com/qTip2/qTip2) | [qTip2/qTip2](https://github.com/qTip2/qTip2) | Pretty powerful tooltips. | ![GitHub](https://img.shields.io/github/stars/qTip2/qTip2) |
| [tooltipster](https://github.com/iamceege/tooltipster) | [iamceege/tooltipster](https://github.com/iamceege/tooltipster) | A jQuery tooltip plugin. | ![GitHub](https://img.shields.io/github/stars/iamceege/tooltipster) |
| [simptip](https://github.com/arashmanteghi/simptip) | [arashmanteghi/simptip](https://github.com/arashmanteghi/simptip) | A simple CSS tooltip made with Sass. | ![GitHub](https://img.shields.io/github/stars/arashmanteghi/simptip) |
| [toolbar](https://github.com/paulkinzett/toolbar) | [paulkinzett/toolbar](https://github.com/paulkinzett/toolbar) | A tooltip style toolbar jQuery plugin | ![GitHub](https://img.shields.io/github/stars/paulkinzett/toolbar) |
| [hint.css](https://github.com/chinchang/hint.css) | [chinchang/hint.css](https://github.com/chinchang/hint.css) | A tooltip library in CSS for your lovely websites. | ![GitHub](https://img.shields.io/github/stars/chinchang/hint.css) |


## Modals and Popups

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) | [dimsemenov/Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) | Light and responsive lightbox script with focus on performance. | ![GitHub](https://img.shields.io/github/stars/dimsemenov/Magnific-Popup) |
| [jquery-popbox](https://github.com/gristmill/jquery-popbox) | [gristmill/jquery-popbox](https://github.com/gristmill/jquery-popbox) | jQuery PopBox UI Element. | ![GitHub](https://img.shields.io/github/stars/gristmill/jquery-popbox) |
| [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) | [voronianski/jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) | A jQuery plugin with new modal concept for popups. | ![GitHub](https://img.shields.io/github/stars/voronianski/jquery.avgrund.js) |
| [vex](https://github.com/HubSpot/vex) | [HubSpot/vex](https://github.com/HubSpot/vex) | A modern dialog library which is highly configurable and easy to style. | ![GitHub](https://img.shields.io/github/stars/HubSpot/vex) |
| [bootstrap-modal](https://github.com/jschr/bootstrap-modal) | [jschr/bootstrap-modal](https://github.com/jschr/bootstrap-modal) | Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more. | ![GitHub](https://img.shields.io/github/stars/jschr/bootstrap-modal) |
| [css-modal](https://github.com/drublic/css-modal) | [drublic/css-modal](https://github.com/drublic/css-modal) | A modal built out of pure CSS. | ![GitHub](https://img.shields.io/github/stars/drublic/css-modal) |
| [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) | [vast-engineering/jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) | jQuery plugin for responsive and accessible modal windows and tooltips. | ![GitHub](https://img.shields.io/github/stars/vast-engineering/jquery-popup-overlay) |
| [SweetAlert](https://github.com/t4t5/sweetalert) | [t4t5/sweetalert](https://github.com/t4t5/sweetalert) | An awesome replacement for JavaScript's alert. | ![GitHub](https://img.shields.io/github/stars/t4t5/sweetalert) |
| [SweetAlert2](https://github.com/sweetalert2/sweetalert2) | [sweetalert2/sweetalert2](https://github.com/sweetalert2/sweetalert2) | An awesome replacement for JavaScript's alert. | ![GitHub](https://img.shields.io/github/stars/sweetalert2/sweetalert2) |
| [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) | [feimosi/baguetteBox.js](https://github.com/feimosi/baguetteBox.js) | Simple and easy to use lightbox script written in pure JavaScript. | ![GitHub](https://img.shields.io/github/stars/feimosi/baguetteBox.js) |
| [colorbox](https://github.com/jackmoore/colorbox) | [jackmoore/colorbox](https://github.com/jackmoore/colorbox) | A light-weight, customizable lightbox plugin for jQuery. | ![GitHub](https://img.shields.io/github/stars/jackmoore/colorbox) |
| [fancyBox](https://github.com/fancyapps/fancyBox) | [fancyapps/fancyBox](https://github.com/fancyapps/fancyBox) | A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages. | ![GitHub](https://img.shields.io/github/stars/fancyapps/fancyBox) |
| [swipebox](https://github.com/brutaldesign/swipebox) | [brutaldesign/swipebox](https://github.com/brutaldesign/swipebox) | A touchable jQuery lightbox | ![GitHub](https://img.shields.io/github/stars/brutaldesign/swipebox) |
| [jBox](https://github.com/StephanWagner/jBox) | [StephanWagner/jBox](https://github.com/StephanWagner/jBox) | jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more. | ![GitHub](https://img.shields.io/github/stars/StephanWagner/jBox) |
| [lightGallery](https://github.com/sachinchoolur/lightGallery) | [sachinchoolur/lightGallery](https://github.com/sachinchoolur/lightGallery) | A customizable, modular, responsive, lightbox gallery plugin for jQuery. | ![GitHub](https://img.shields.io/github/stars/sachinchoolur/lightGallery) |
| [keukenhof](https://github.com/Alexandrshy/keukenhof) | [Alexandrshy/keukenhof](https://github.com/Alexandrshy/keukenhof) | Lightweight, no dependencies, accessibility enabled TypeScript library for creating modal windows. | ![GitHub](https://img.shields.io/github/stars/Alexandrshy/keukenhof) |
| [screenfull.js](https://github.com/sindresorhus/screenfull.js) | [sindresorhus/screenfull.js](https://github.com/sindresorhus/screenfull.js) | the JavaScript Fullscreen API, which lets you bring the page or any element into fullscreen. Smoothens out the browser implementation differences, so you don't have to. | ![GitHub](https://img.shields.io/github/stars/sindresorhus/screenfull.js) |


## Scroll

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [scrollMonitor](https://github.com/stutrek/scrollMonitor) | [stutrek/scrollMonitor](https://github.com/stutrek/scrollMonitor) | A simple and fast API to monitor elements as you scroll. | ![GitHub](https://img.shields.io/github/stars/stutrek/scrollMonitor) |
| [headroom](https://github.com/WickyNilliams/headroom.js) | [WickyNilliams/headroom.js](https://github.com/WickyNilliams/headroom.js) | Give your pages some headroom. Hide your header until you need it. | ![GitHub](https://img.shields.io/github/stars/WickyNilliams/headroom.js) |
| [onepage-scroll](https://github.com/peachananr/onepage-scroll) | [peachananr/onepage-scroll](https://github.com/peachananr/onepage-scroll) | Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin. | ![GitHub](https://img.shields.io/github/stars/peachananr/onepage-scroll) |
| [iscroll](https://github.com/cubiq/iscroll) | [cubiq/iscroll](https://github.com/cubiq/iscroll) | iScroll is a high performance, small footprint, dependency free, multi-platform JavaScript scroller. | ![GitHub](https://img.shields.io/github/stars/cubiq/iscroll) |
| [skrollr](https://github.com/Prinzhorn/skrollr) | [Prinzhorn/skrollr](https://github.com/Prinzhorn/skrollr) | Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery. | ![GitHub](https://img.shields.io/github/stars/Prinzhorn/skrollr) |
| [parallax](https://github.com/wagerfield/parallax) | [wagerfield/parallax](https://github.com/wagerfield/parallax) | Parallax Engine that reacts to the orientation of a smart device. | ![GitHub](https://img.shields.io/github/stars/wagerfield/parallax) |
| [stellar.js](https://github.com/markdalgleish/stellar.js) | [markdalgleish/stellar.js](https://github.com/markdalgleish/stellar.js) | Parallax scrolling made easy. | ![GitHub](https://img.shields.io/github/stars/markdalgleish/stellar.js) |
| [plax](https://github.com/cameronmcefee/plax) | [cameronmcefee/plax](https://github.com/cameronmcefee/plax) | jQuery powered parallaxing. | ![GitHub](https://img.shields.io/github/stars/cameronmcefee/plax) |
| [jparallax](https://github.com/stephband/jparallax) | [stephband/jparallax](https://github.com/stephband/jparallax) | jQuery plugin for creating interactive parallax effect. | ![GitHub](https://img.shields.io/github/stars/stephband/jparallax) |
| [fullPage](https://github.com/alvarotrigo/fullPage.js) | [alvarotrigo/fullPage.js](https://github.com/alvarotrigo/fullPage.js) | A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites). | ![GitHub](https://img.shields.io/github/stars/alvarotrigo/fullPage.js) |
| [ScrollMenu](https://github.com/s-yadav/ScrollMenu) | [s-yadav/ScrollMenu](https://github.com/s-yadav/ScrollMenu) | A new interface to replace old boring scrollbar. | ![GitHub](https://img.shields.io/github/stars/s-yadav/ScrollMenu) |
| [Clusterize.js](https://github.com/NeXTs/Clusterize.js) | [NeXTs/Clusterize.js](https://github.com/NeXTs/Clusterize.js) | Tiny vanilla JS plugin to display large data sets easily. | ![GitHub](https://img.shields.io/github/stars/NeXTs/Clusterize.js) |
| [simpleParallax](https://github.com/geosigno/simpleParallax) | [geosigno/simpleParallax](https://github.com/geosigno/simpleParallax) | Simple and tiny JavaScript library to add parallax animations on any images | ![GitHub](https://img.shields.io/github/stars/geosigno/simpleParallax) |
| [rellax](https://github.com/dixonandmoe/rellax) | [dixonandmoe/rellax](https://github.com/dixonandmoe/rellax) | Buttery smooth, super lightweight, vanilla javascript parallax library. | ![GitHub](https://img.shields.io/github/stars/dixonandmoe/rellax) |
| [asscroll](https://github.com/ashthornton/asscroll) | [ashthornton/asscroll](https://github.com/ashthornton/asscroll) | A hybrid smooth scroll setup that combines the performance gains of virtual scroll with the reliability of native scroll. | ![GitHub](https://img.shields.io/github/stars/ashthornton/asscroll) |
| [stroll](https://github.com/hakimel/stroll.js) | [hakimel/stroll.js](https://github.com/hakimel/stroll.js) | A collection of CSS List scroll effects bind to dom through javascript. | ![GitHub](https://img.shields.io/github/stars/hakimel/stroll.js) |
| [locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) | [locomotivemtl/locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) | Detects the elements in viewport and smooth scrolling with parallax. | ![GitHub](https://img.shields.io/github/stars/locomotivemtl/locomotive-scroll) |
| [elevator.js](https://github.com/tholman/elevator.js) | [tholman/elevator.js](https://github.com/tholman/elevator.js) | Finally, a "back to top" button that behaves like a real elevator. | ![GitHub](https://img.shields.io/github/stars/tholman/elevator.js) |


## Menu

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) | [kamens/jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) | jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's. | ![GitHub](https://img.shields.io/github/stars/kamens/jQuery-menu-aim) |
| [jQuery contextMenu](https://github.com/swisnl/jQuery-contextMenu) | [swisnl/jQuery-contextMenu](https://github.com/swisnl/jQuery-contextMenu) | contextMenu manager. | ![GitHub](https://img.shields.io/github/stars/swisnl/jQuery-contextMenu) |
| [Slideout](https://github.com/mango/slideout) | [mango/slideout](https://github.com/mango/slideout) | A responsive touch slideout navigation menu for mobile web apps. | ![GitHub](https://img.shields.io/github/stars/mango/slideout) |
| [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) | [JoanClaret/slide-and-swipe-menu](https://github.com/JoanClaret/slide-and-swipe-menu) | A sliding swipe menu that works with touchSwipe library. | ![GitHub](https://img.shields.io/github/stars/JoanClaret/slide-and-swipe-menu) |
| [mmenu](https://github.com/FrDH/jQuery.mmenu) | [FrDH/jQuery.mmenu](https://github.com/FrDH/jQuery.mmenu) | The best jQuery plugin for app look-alike on- and off-canvas menus with sliding submenus for your website and webapp. | ![GitHub](https://img.shields.io/github/stars/FrDH/jQuery.mmenu) |


## Table/Grid

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [jTable](https://github.com/hikalkan/jtable) | [hikalkan/jtable](https://github.com/hikalkan/jtable) | A jQuery plugin to create AJAX based CRUD tables. | ![GitHub](https://img.shields.io/github/stars/hikalkan/jtable) |
| [DataTables](https://www.datatables.net/) | - | (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table. |  |
| [Tabulator](http://olifolkerd.github.io/tabulator/) | - | (jQuery plug-in) An extremely flexible library that create tables with a range of interactive features from any JSON data source or existing HTML table. |  |
| [Bootstrap Table](https://bootstrap-table.com/) | - | An Extension to the popular Bootstrap framework for creating tables that fit the style of your site with no need for additional markup. |  |
| [floatThead](https://github.com/mkoryak/floatThead) | [mkoryak/floatThead](https://github.com/mkoryak/floatThead) | (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css. | ![GitHub](https://img.shields.io/github/stars/mkoryak/floatThead) |
| [Masonry](https://masonry.desandro.com/) | - | A cascading grid layout library. |  |
| [Packery](https://packery.metafizzy.co/) | - | A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts. |  |
| [Isotope](https://isotope.metafizzy.co/) | - | A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts. |  |
| [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) | [kristoferjoseph/flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid) | Grid based on CSS3 flexbox. | ![GitHub](https://img.shields.io/github/stars/kristoferjoseph/flexboxgrid) |


## Frameworks

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Semantic UI](https://semantic-ui.com/) | - | UI Kit with lots of themes and elements. |  |
| [w2ui](http://w2ui.com/) | - | A set of jQuery plugins for front-end development of data-driven web applications. |  |
| [fluidity](https://github.com/mrmrs/fluidity) | [mrmrs/fluidity](https://github.com/mrmrs/fluidity) | The worlds smallest fully-responsive css framework. | ![GitHub](https://img.shields.io/github/stars/mrmrs/fluidity) |
| [Ink](https://github.com/sapo/Ink) | [sapo/Ink](https://github.com/sapo/Ink) | An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping. | ![GitHub](https://img.shields.io/github/stars/sapo/Ink) |
| [DataFormsJS](https://github.com/dataformsjs/dataformsjs) | [dataformsjs/dataformsjs](https://github.com/dataformsjs/dataformsjs) | A minimal JavaScript Framework and standalone components for rapid development of sites and SPA's. | ![GitHub](https://img.shields.io/github/stars/dataformsjs/dataformsjs) |
| [EHTML](https://github.com/Guseyn/EHTML) | [Guseyn/EHTML](https://github.com/Guseyn/EHTML) | HTML Framework that allows you not to write JavaScript code. | ![GitHub](https://img.shields.io/github/stars/Guseyn/EHTML) |


## Boilerplates

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | A professional front-end template for building fast, robust, and adaptable web apps or sites. | ![GitHub](https://img.shields.io/github/stars/h5bp/html5-boilerplate) |
| [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) | [h5bp/mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) | A front-end template that helps you build fast, modern mobile web apps. | ![GitHub](https://img.shields.io/github/stars/h5bp/mobile-boilerplate) |
| [webplate](https://github.com/chrishumboldt/webplate) | [chrishumboldt/webplate](https://github.com/chrishumboldt/webplate) | An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use. | ![GitHub](https://img.shields.io/github/stars/chrishumboldt/webplate) |
| [Cerberus](https://github.com/TedGoas/Cerberus) | [TedGoas/Cerberus](https://github.com/TedGoas/Cerberus) | A few simple, but solid patterns for responsive HTML emails. Even in Outlook. | ![GitHub](https://img.shields.io/github/stars/TedGoas/Cerberus) |
| [full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) | [CodyHouse/full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) | An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation. | ![GitHub](https://img.shields.io/github/stars/CodyHouse/full-page-intro-and-navigation) |
| [Fluid-Squares](https://github.com/crozynski/Fluid-Squares) | [crozynski/Fluid-Squares](https://github.com/crozynski/Fluid-Squares) | A fluid grid of square units. | ![GitHub](https://img.shields.io/github/stars/crozynski/Fluid-Squares) |
| [Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) | [bradfrost/Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) | An example of a mobile-first responsive web design. | ![GitHub](https://img.shields.io/github/stars/bradfrost/Mobile-First-RWD) |
| [this-is-responsive](https://github.com/bradfrost/this-is-responsive) | [bradfrost/this-is-responsive](https://github.com/bradfrost/this-is-responsive) | This Is Responsive. | ![GitHub](https://img.shields.io/github/stars/bradfrost/this-is-responsive) |
| [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) | [addyosmani/9f10c555e32a8d06ddb0](https://github.com/addyosmani/9f10c555e32a8d06ddb0) | Task automation with NPM run-scripts. | ![GitHub](https://img.shields.io/github/stars/addyosmani/9f10c555e32a8d06ddb0) |
| [Wasp](https://github.com/wasp-lang/wasp) | [wasp-lang/wasp](https://github.com/wasp-lang/wasp) | Wasp is a declarative domain-specific language for developing, building, and deploying modern Javascript full-stack web apps with less code. | ![GitHub](https://img.shields.io/github/stars/wasp-lang/wasp) |


## Images

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Drift](https://github.com/imgix/drift) | [imgix/drift](https://github.com/imgix/drift) | Easily add "zoom on hover" functionality to your site's images. Lightweight, no-dependency JavaScript. | ![GitHub](https://img.shields.io/github/stars/imgix/drift) |
| [Magnificent.js](https://github.com/AndersDJohnson/magnificent.js) | [AndersDJohnson/magnificent.js](https://github.com/AndersDJohnson/magnificent.js) | Zoom responsively, images & more, w/ jQuery. | ![GitHub](https://img.shields.io/github/stars/AndersDJohnson/magnificent.js) |
| [Panolens.js](https://github.com/pchen66/panolens.js) | [pchen66/panolens.js](https://github.com/pchen66/panolens.js) | Panolens.js is an event-driven and WebGL based panorama viewer. Lightweight and flexible | ![GitHub](https://img.shields.io/github/stars/pchen66/panolens.js) |


## Gesture

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [hammer.js](https://github.com/hammerjs/hammer.js) | [hammerjs/hammer.js](https://github.com/hammerjs/hammer.js) | A JavaScript library for multi-touch gestures. | ![GitHub](https://img.shields.io/github/stars/hammerjs/hammer.js) |
| [touchemulator](https://github.com/hammerjs/touchemulator) | [hammerjs/touchemulator](https://github.com/hammerjs/touchemulator) | Emulate touch input on your desktop. | ![GitHub](https://img.shields.io/github/stars/hammerjs/touchemulator) |
| [Dragula](https://github.com/bevacqua/dragula/) | [bevacqua/dragula](https://github.com/bevacqua/dragula) | Drag and drop so simple it hurts. | ![GitHub](https://img.shields.io/github/stars/bevacqua/dragula) |


## Maps

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Leaflet](https://github.com/Leaflet/Leaflet) | [Leaflet/Leaflet](https://github.com/Leaflet/Leaflet) | JavaScript library for mobile-friendly interactive maps. | ![GitHub](https://img.shields.io/github/stars/Leaflet/Leaflet) |
| [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) | [AnalyticalGraphicsInc/cesium](https://github.com/AnalyticalGraphicsInc/cesium) | Open Source WebGL virtual globe and map engine. | ![GitHub](https://img.shields.io/github/stars/AnalyticalGraphicsInc/cesium) |
| [gmaps](https://github.com/HPNeo/gmaps) | [HPNeo/gmaps](https://github.com/HPNeo/gmaps) | The easiest way to use Google Maps. | ![GitHub](https://img.shields.io/github/stars/HPNeo/gmaps) |
| [polymaps](https://github.com/simplegeo/polymaps) | [simplegeo/polymaps](https://github.com/simplegeo/polymaps) | A free JavaScript library for making dynamic, interactive maps in modern web browsers. | ![GitHub](https://img.shields.io/github/stars/simplegeo/polymaps) |
| [kartograph.js](https://github.com/kartograph/kartograph.js) | [kartograph/kartograph.js](https://github.com/kartograph/kartograph.js) | Open source JavaScript renderer for Kartograph SVG maps. | ![GitHub](https://img.shields.io/github/stars/kartograph/kartograph.js) |
| [mapbox.js](https://github.com/mapbox/mapbox.js) | [mapbox/mapbox.js](https://github.com/mapbox/mapbox.js) | Mapbox JavaScript API, a Leaflet Plugin. | ![GitHub](https://img.shields.io/github/stars/mapbox/mapbox.js) |
| [jqvmap](https://github.com/manifestinteractive/jqvmap) | [manifestinteractive/jqvmap](https://github.com/manifestinteractive/jqvmap) | jQuery Vector Map Library. | ![GitHub](https://img.shields.io/github/stars/manifestinteractive/jqvmap) |
| [OpenLayers3](https://openlayers.org/) | - | A high-performance, feature-packed library for all your mapping needs. |  |
| [H3js](https://github.com/uber/h3) | [uber/h3](https://github.com/uber/h3) | Hexagonal hierarchical geospatial indexing system ported to javascript by Uber for geospatial visualization. | ![GitHub](https://img.shields.io/github/stars/uber/h3) |


## Video/Audio

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) | [mike-zarandona/prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) | Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support. | ![GitHub](https://img.shields.io/github/stars/mike-zarandona/prettyembed.js) |
| [Play-em JS](https://github.com/adrienjoly/playemjs) | [adrienjoly/playemjs](https://github.com/adrienjoly/playemjs) | Play'em is a JavaScript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo. | ![GitHub](https://img.shields.io/github/stars/adrienjoly/playemjs) |
| [polyplayer](https://github.com/Acconut/polyplayer) | [Acconut/polyplayer](https://github.com/Acconut/polyplayer) | Rule YouTube, Soundcloud and Vimeo player with one API. | ![GitHub](https://img.shields.io/github/stars/Acconut/polyplayer) |
| [flowplayer](https://flowplayer.com/) | [flowplayer/flowplayer](https://github.com/flowplayer/flowplayer) | The HTML5 video player for the web | ![GitHub](https://img.shields.io/github/stars/flowplayer/flowplayer) |
| [mediaelement](https://github.com/johndyer/mediaelement) | [johndyer/mediaelement](https://github.com/johndyer/mediaelement) | HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://www.mediaelementjs.com/> | ![GitHub](https://img.shields.io/github/stars/johndyer/mediaelement) |
| [SoundJS](https://github.com/CreateJS/SoundJS) | [CreateJS/SoundJS](https://github.com/CreateJS/SoundJS) | A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers. | ![GitHub](https://img.shields.io/github/stars/CreateJS/SoundJS) |
| [video.js](https://github.com/videojs/video.js) | [videojs/video.js](https://github.com/videojs/video.js) | Video.js - open source HTML5 & Flash video player. | ![GitHub](https://img.shields.io/github/stars/videojs/video.js) |
| [FitVids.js](https://github.com/davatron5000/FitVids.js) | [davatron5000/FitVids.js](https://github.com/davatron5000/FitVids.js) | A lightweight, easy-to-use jQuery plugin for fluid width video embeds. | ![GitHub](https://img.shields.io/github/stars/davatron5000/FitVids.js) |
| [Ion.Sound](https://github.com/IonDen/ion.sound) | [IonDen/ion.sound](https://github.com/IonDen/ion.sound) | Simple sounds on any web page. | ![GitHub](https://img.shields.io/github/stars/IonDen/ion.sound) |
| [photobooth-js](https://github.com/WolframHempel/photobooth-js) | [WolframHempel/photobooth-js](https://github.com/WolframHempel/photobooth-js) | A widget that allows users to take their avatar pictures on your site. | ![GitHub](https://img.shields.io/github/stars/WolframHempel/photobooth-js) |
| [clappr](https://github.com/clappr/clappr) | [clappr/clappr](https://github.com/clappr/clappr) | An extensible media player for the web http://clappr.io | ![GitHub](https://img.shields.io/github/stars/clappr/clappr) |
| [ts-audio](https://github.com/EvandroLG/ts-audio) | [EvandroLG/ts-audio](https://github.com/EvandroLG/ts-audio) | an agnostic and easy-to-use library to work with the `AudioContext` API. | ![GitHub](https://img.shields.io/github/stars/EvandroLG/ts-audio) |
| [AmplitudeJS](https://521dimensions.com/open-source/amplitudejs) | - | Open Source HTML5 Web Audio Library. Design your web audio player, the way you want. No dependencies required. |  |
| [ractive-player](https://github.com/ysulyma/ractive-player) | [ysulyma/ractive-player](https://github.com/ysulyma/ractive-player) | A library for making interactive videos in React.js. | ![GitHub](https://img.shields.io/github/stars/ysulyma/ractive-player) |
| [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | FFmpeg optimized for in-browser use: minimal size for faster loading, asm.js, performance tunings, etc. | ![GitHub](https://img.shields.io/github/stars/Kagami/ffmpeg.js) |
| [flv.js](https://github.com/bilibili/flv.js) | [bilibili/flv.js](https://github.com/bilibili/flv.js) | An HTML5 Flash Video (FLV) Player written in pure JavaScript without Flash. | ![GitHub](https://img.shields.io/github/stars/bilibili/flv.js) |
| [hls.js](https://github.com/video-dev/hls.js) | [video-dev/hls.js](https://github.com/video-dev/hls.js) | A JavaScript library that implements an HTTP Live Streaming client. It relies on HTML5 video and MediaSource Extensions for playback. | ![GitHub](https://img.shields.io/github/stars/video-dev/hls.js) |


## Typography

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [FlowType.JS](https://github.com/simplefocus/FlowType.JS) | [simplefocus/FlowType.JS](https://github.com/simplefocus/FlowType.JS) | Web typography at its finest: font-size and line-height based on element width. | ![GitHub](https://img.shields.io/github/stars/simplefocus/FlowType.JS) |
| [BigText](https://github.com/zachleat/BigText) | [zachleat/BigText](https://github.com/zachleat/BigText) | jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width. | ![GitHub](https://img.shields.io/github/stars/zachleat/BigText) |
| [circletype](https://github.com/peterhry/circletype) | [peterhry/circletype](https://github.com/peterhry/circletype) | A jQuery plugin that lets you curve type on the web. | ![GitHub](https://img.shields.io/github/stars/peterhry/circletype) |
| [slabText](https://github.com/freqDec/slabText/) | [freqDec/slabText](https://github.com/freqDec/slabText) | A jQuery plugin for producing big, bold & responsive headlines. | ![GitHub](https://img.shields.io/github/stars/freqDec/slabText) |
| [simple-text-rotator](https://github.com/peachananr/simple-text-rotator) | [peachananr/simple-text-rotator](https://github.com/peachananr/simple-text-rotator) | Add a super simple rotating text to your website with little to no markup. | ![GitHub](https://img.shields.io/github/stars/peachananr/simple-text-rotator) |
| [novacancy.js](https://github.com/chuckyglitch/novacancy.js) | [chuckyglitch/novacancy.js](https://github.com/chuckyglitch/novacancy.js) | Text Neon Golden effect jQuery plug-in. | ![GitHub](https://img.shields.io/github/stars/chuckyglitch/novacancy.js) |
| [jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) | [ghepting/jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) | Make your text sizing responsive! | ![GitHub](https://img.shields.io/github/stars/ghepting/jquery-responsive-text) |
| [FitText.js](https://github.com/davatron5000/FitText.js) | [davatron5000/FitText.js](https://github.com/davatron5000/FitText.js) | A jQuery plugin for inflating web type. | ![GitHub](https://img.shields.io/github/stars/davatron5000/FitText.js) |
| [Lettering.js](https://github.com/davatron5000/Lettering.js) | [davatron5000/Lettering.js](https://github.com/davatron5000/Lettering.js) | A lightweight, easy to use JavaScript `<span>` injector for radical Web Typography. | ![GitHub](https://img.shields.io/github/stars/davatron5000/Lettering.js) |


## Animations

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [velocity](https://github.com/julianshapiro/velocity) | [julianshapiro/velocity](https://github.com/julianshapiro/velocity) | Accelerated JavaScript animation. | ![GitHub](https://img.shields.io/github/stars/julianshapiro/velocity) |
| [jquery.transit](https://github.com/rstacruz/jquery.transit) | [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | Super-smooth CSS3 transformations and transitions for jQuery. | ![GitHub](https://img.shields.io/github/stars/rstacruz/jquery.transit) |
| [bounce.js](https://github.com/tictail/bounce.js) | [tictail/bounce.js](https://github.com/tictail/bounce.js) | Create tasty CSS3 powered animations in no time. | ![GitHub](https://img.shields.io/github/stars/tictail/bounce.js) |
| [GreenSock-JS](https://github.com/greensock/GreenSock-JS) | [greensock/GreenSock-JS](https://github.com/greensock/GreenSock-JS) | High-performance HTML5 animations that work in all major browsers. | ![GitHub](https://img.shields.io/github/stars/greensock/GreenSock-JS) |
| [TransitionEnd](https://github.com/EvandroLG/transitionEnd) | [EvandroLG/transitionEnd](https://github.com/EvandroLG/transitionEnd) | TransitionEnd is an agnostic and cross-browser library to work with transitioned event. | ![GitHub](https://img.shields.io/github/stars/EvandroLG/transitionEnd) |
| [Dynamic.js](https://github.com/michaelvillar/dynamics.js) | [michaelvillar/dynamics.js](https://github.com/michaelvillar/dynamics.js) | JavaScript library to create physics-based CSS animations. | ![GitHub](https://img.shields.io/github/stars/michaelvillar/dynamics.js) |
| [the-cube](https://github.com/pstadler/the-cube) | [pstadler/the-cube](https://github.com/pstadler/the-cube) | The Cube is an experiment with CSS3 transitions. | ![GitHub](https://img.shields.io/github/stars/pstadler/the-cube) |
| [Effeckt.css](https://github.com/h5bp/Effeckt.css) | [h5bp/Effeckt.css](https://github.com/h5bp/Effeckt.css) | A Performant Transitions and Animations Library. | ![GitHub](https://img.shields.io/github/stars/h5bp/Effeckt.css) |
| [animate.css](https://github.com/daneden/animate.css) | [daneden/animate.css](https://github.com/daneden/animate.css) | A cross-browser library of CSS animations. As easy to use as an easy thing. | ![GitHub](https://img.shields.io/github/stars/daneden/animate.css) |
| [textillate](https://github.com/jschr/textillate) | [jschr/textillate](https://github.com/jschr/textillate) | A simple plugin for CSS3 text animations. | ![GitHub](https://img.shields.io/github/stars/jschr/textillate) |
| [move.js](https://github.com/visionmedia/move.js) | [visionmedia/move.js](https://github.com/visionmedia/move.js) | CSS3 backed JavaScript animation framework. | ![GitHub](https://img.shields.io/github/stars/visionmedia/move.js) |
| [animatable](https://github.com/LeaVerou/animatable) | [LeaVerou/animatable](https://github.com/LeaVerou/animatable) | One property, two values, endless possibilities. | ![GitHub](https://img.shields.io/github/stars/LeaVerou/animatable) |
| [shuffle-images](https://github.com/peachananr/shuffle-images) | [peachananr/shuffle-images](https://github.com/peachananr/shuffle-images) | The Simplest Way to shuffle through images in a Creative Way. | ![GitHub](https://img.shields.io/github/stars/peachananr/shuffle-images) |
| [smoothState.js](https://github.com/miguel-perez/smoothState.js) | [miguel-perez/smoothState.js](https://github.com/miguel-perez/smoothState.js) | Unobtrusive page transitions with jQuery. | ![GitHub](https://img.shields.io/github/stars/miguel-perez/smoothState.js) |
| [Anime.js](https://animejs.com/) | - | A JavaScript animation engine. |  |
| [Mo.js](https://mojs.github.io/) | - | Motion graphics toolbelt for the web. |  |
| [particles.js](https://github.com/VincentGarreau/particles.js) | [VincentGarreau/particles.js](https://github.com/VincentGarreau/particles.js) | A lightweight JavaScript library for creating particles. | ![GitHub](https://img.shields.io/github/stars/VincentGarreau/particles.js) |
| [tsParticles](https://github.com/matteobruni/tsparticles) | [matteobruni/tsparticles](https://github.com/matteobruni/tsparticles) | A new and improved version of particles.js with bug fixes and many new features. | ![GitHub](https://img.shields.io/github/stars/matteobruni/tsparticles) |
| [particles-bg](https://github.com/lindelof/particles-bg) | [lindelof/particles-bg](https://github.com/lindelof/particles-bg) | A lightweight React particles animation background component. | ![GitHub](https://img.shields.io/github/stars/lindelof/particles-bg) |
| [barbajs](https://github.com/barbajs/barba) | [barbajs/barba](https://github.com/barbajs/barba) | It helps you create fluid and smooth transitions between your website's pages. | ![GitHub](https://img.shields.io/github/stars/barbajs/barba) |
| [typicaljs](https://github.com/camwiegert/typical) | [camwiegert/typical](https://github.com/camwiegert/typical) | Animated typing in ~400 bytes 🐡 of JavaScript | ![GitHub](https://img.shields.io/github/stars/camwiegert/typical) |
| [AutoAnimate](https://auto-animate.formkit.com) | - | Add motion to your apps with a single line of code. |  |


## Image Processing

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [lena.js](https://github.com/davidsonfellipe/lena.js) | [davidsonfellipe/lena.js](https://github.com/davidsonfellipe/lena.js) | A Library for image processing with filters and util functions. | ![GitHub](https://img.shields.io/github/stars/davidsonfellipe/lena.js) |
| [pica](https://github.com/nodeca/pica) | [nodeca/pica](https://github.com/nodeca/pica) | High quality image resize (with fast Lanczos filter, implemented in pure JS). | ![GitHub](https://img.shields.io/github/stars/nodeca/pica) |
| [cropper](https://github.com/fengyuanchen/cropper) | [fengyuanchen/cropper](https://github.com/fengyuanchen/cropper) | A simple jQuery image cropping plugin. | ![GitHub](https://img.shields.io/github/stars/fengyuanchen/cropper) |


## ES6

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [es6features](https://github.com/lukehoban/es6features) | [lukehoban/es6features](https://github.com/lukehoban/es6features) | Overview of ECMAScript 6 features. | ![GitHub](https://img.shields.io/github/stars/lukehoban/es6features) |
| [es6-features](https://github.com/rse/es6-features) | [rse/es6-features](https://github.com/rse/es6-features) | ECMAScript 6: Feature Overview & Comparison. | ![GitHub](https://img.shields.io/github/stars/rse/es6-features) |
| [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) | [DrkSephy/es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) | ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets. | ![GitHub](https://img.shields.io/github/stars/DrkSephy/es6-cheatsheet) |
| [ECMAScript 6 compatibility table](https://compat-table.github.io/compat-table/es6/) | - | Compatibility tables for all ECMAScript 6 features on a variety of environments. |  |
| [Babel (Formerly 6to5)](https://github.com/babel/babel) | [babel/babel](https://github.com/babel/babel) | Turn ES6+ code into vanilla ES5 with no runtime. | ![GitHub](https://img.shields.io/github/stars/babel/babel) |
| [Traceur compiler](https://github.com/google/traceur-compiler) | [google/traceur-compiler](https://github.com/google/traceur-compiler) | ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more. | ![GitHub](https://img.shields.io/github/stars/google/traceur-compiler) |


## Generators

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Gatsby.js](https://github.com/gatsbyjs/gatsby) | [gatsbyjs/gatsby](https://github.com/gatsbyjs/gatsby) | React-based static site generator. | ![GitHub](https://img.shields.io/github/stars/gatsbyjs/gatsby) |
| [Gridsome](https://github.com/gridsome/gridsome) | [gridsome/gridsome](https://github.com/gridsome/gridsome) | Vue-powered static site generator. | ![GitHub](https://img.shields.io/github/stars/gridsome/gridsome) |
| [Docusaurus](https://github.com/facebook/docusaurus) | [facebook/docusaurus](https://github.com/facebook/docusaurus) | React-based static site generator by Facebook, ideal for content-centric websites. | ![GitHub](https://img.shields.io/github/stars/facebook/docusaurus) |
| [Next.js](https://github.com/vercel/next.js) | [vercel/next.js](https://github.com/vercel/next.js) | React powered static site generator, and they say "All the tools you need to make the Web. Faster.". | ![GitHub](https://img.shields.io/github/stars/vercel/next.js) |
| [Lume](https://github.com/lumeland/lume) | [lumeland/lume](https://github.com/lumeland/lume) | Static site generator for Deno. | ![GitHub](https://img.shields.io/github/stars/lumeland/lume) |
| [Astro](https://github.com/withastro/astro) | [withastro/astro](https://github.com/withastro/astro) | The web framework for content-driven websites. | ![GitHub](https://img.shields.io/github/stars/withastro/astro) |


## SDK

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) | [huei90/javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) | JavaScript SDK design guide extracted from work and personal experience. | ![GitHub](https://img.shields.io/github/stars/huei90/javascript-sdk-design) |
| [Spotify SDK](https://github.com/loverajoel/spotify-sdk) | [loverajoel/spotify-sdk](https://github.com/loverajoel/spotify-sdk) | Entity oriented SDK to work with the Spotify Web API. | ![GitHub](https://img.shields.io/github/stars/loverajoel/spotify-sdk) |
| [Square Node.js SDK](https://github.com/square/connect-nodejs-sdk/) | [square/connect-nodejs-sdk](https://github.com/square/connect-nodejs-sdk) | JavaScript client library for payments and other Square APIs. | ![GitHub](https://img.shields.io/github/stars/square/connect-nodejs-sdk) |
| [OpenAI SDK](https://github.com/openai/openai-node) | [openai/openai-node](https://github.com/openai/openai-node) | Official JavaScript / TypeScript library for the OpenAI API. | ![GitHub](https://img.shields.io/github/stars/openai/openai-node) |


## Full Text Search

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [lunr](https://github.com/olivernn/lunr.js) | [olivernn/lunr.js](https://github.com/olivernn/lunr.js) | Library for use in the browser and It indexes JSON documents and provides a simple search interface for retrieving documents that best match text queries. | ![GitHub](https://img.shields.io/github/stars/olivernn/lunr.js) |
| [flexsearch](https://github.com/nextapps-de/flexsearch) | [nextapps-de/flexsearch](https://github.com/nextapps-de/flexsearch) | It is a Next-Generation full text search library for Browser and Node.js. | ![GitHub](https://img.shields.io/github/stars/nextapps-de/flexsearch) |
| [Elasticlunr](https://github.com/weixsong/elasticlunr.js) | [weixsong/elasticlunr.js](https://github.com/weixsong/elasticlunr.js) | This library is based on lunr.js, but more flexible and customized. | ![GitHub](https://img.shields.io/github/stars/weixsong/elasticlunr.js) |


## ORM

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Prisma](https://github.com/prisma/prisma) | [prisma/prisma](https://github.com/prisma/prisma) | Next-generation ORM for Node.js & TypeScript \| PostgreSQL, MySQL, MariaDB, SQL Server, SQLite, MongoDB and CockroachDB. | ![GitHub](https://img.shields.io/github/stars/prisma/prisma) |
| [Sequelize](https://github.com/sequelize/sequelize) | [sequelize/sequelize](https://github.com/sequelize/sequelize) | Feature-rich ORM for modern Node.js and TypeScript \| PostgreSQL, MySQL, MariaDB, SQLite, MS SQL Server, Snowflake, Oracle DB... | ![GitHub](https://img.shields.io/github/stars/sequelize/sequelize) |
| [Mongoose](https://github.com/Automattic/mongoose) | [Automattic/mongoose](https://github.com/Automattic/mongoose) | MongoDB object modeling designed to work in an asynchronous environment. | ![GitHub](https://img.shields.io/github/stars/Automattic/mongoose) |
| [TypeORM](https://github.com/typeorm/typeorm) | [typeorm/typeorm](https://github.com/typeorm/typeorm) | ORM for TypeScript and JavaScript, Works in NodeJS, Browser, Ionic, Cordova and Electron platforms. | ![GitHub](https://img.shields.io/github/stars/typeorm/typeorm) |
| [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) | [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | Headless TypeScript ORM with a head. Runs on Node, Bun and Deno. | ![GitHub](https://img.shields.io/github/stars/drizzle-team/drizzle-orm) |
| [Kysely](https://github.com/kysely-org/kysely) | [kysely-org/kysely](https://github.com/kysely-org/kysely) | A type-safe typescript SQL query builder. | ![GitHub](https://img.shields.io/github/stars/kysely-org/kysely) |
| [Knex](https://github.com/knex/knex) | [knex/knex](https://github.com/knex/knex) | A query builder for PostgreSQL, MySQL, CockroachDB, SQL Server, SQLite3 and Oracle, designed to be flexible, portable, and fun to use. | ![GitHub](https://img.shields.io/github/stars/knex/knex) |
| [MikroORM](https://github.com/mikro-orm/mikro-orm) | [mikro-orm/mikro-orm](https://github.com/mikro-orm/mikro-orm) | TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns. | ![GitHub](https://img.shields.io/github/stars/mikro-orm/mikro-orm) |


## WebSockets

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [Socket.io](https://github.com/socketio/socket.io) | [socketio/socket.io](https://github.com/socketio/socket.io) | The most widely used WebSocket library for real-time applications. Supports auto-reconnection, rooms, and fallbacks (e.g., polling). | ![GitHub](https://img.shields.io/github/stars/socketio/socket.io) |
| [ws](https://github.com/websockets/ws) | [websockets/ws](https://github.com/websockets/ws) | Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js. | ![GitHub](https://img.shields.io/github/stars/websockets/ws) |


## Misc

| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [echo](https://github.com/toddmotto/echo) | [toddmotto/echo](https://github.com/toddmotto/echo) | Lazy-loading images with data-* attributes. | ![GitHub](https://img.shields.io/github/stars/toddmotto/echo) |
| [picturefill](https://github.com/scottjehl/picturefill) | [scottjehl/picturefill](https://github.com/scottjehl/picturefill) | A responsive image polyfill for &lt;picture&gt;, srcset, sizes. | ![GitHub](https://img.shields.io/github/stars/scottjehl/picturefill) |
| [platform.js](https://github.com/bestiejs/platform.js) | [bestiejs/platform.js](https://github.com/bestiejs/platform.js) | A platform detection library that works on nearly all JavaScript platforms. | ![GitHub](https://img.shields.io/github/stars/bestiejs/platform.js) |
| [json3](https://github.com/bestiejs/json3) | [bestiejs/json3](https://github.com/bestiejs/json3) | A modern JSON implementation compatible with nearly all JavaScript platforms. | ![GitHub](https://img.shields.io/github/stars/bestiejs/json3) |
| [Logical Or Not](https://gabinaureche.com/logicalornot/) | - | A game about JavaScript specificities. |  |
| [BitSet.js](https://github.com/infusion/BitSet.js) | [infusion/BitSet.js](https://github.com/infusion/BitSet.js) | A JavaScript Bit-Vector implementation. | ![GitHub](https://img.shields.io/github/stars/infusion/BitSet.js) |
| [spoiler-alert](https://github.com/joshbuddy/spoiler-alert) | [joshbuddy/spoiler-alert](https://github.com/joshbuddy/spoiler-alert) | SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site. | ![GitHub](https://img.shields.io/github/stars/joshbuddy/spoiler-alert) |
| [jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) | [illyism/jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) | Vibration API Wrappers | ![GitHub](https://img.shields.io/github/stars/illyism/jquery.vibrate.js) |
| [list.js](https://listjs.com) | [javve/list.js](https://github.com/javve/list.js) | Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML. | ![GitHub](https://img.shields.io/github/stars/javve/list.js) |
| [mixitup](https://github.com/patrickkunka/mixitup) | [patrickkunka/mixitup](https://github.com/patrickkunka/mixitup) | MixItUp - A Filter & Sort Plugin. | ![GitHub](https://img.shields.io/github/stars/patrickkunka/mixitup) |
| [grid](https://github.com/hootsuite/grid) | [hootsuite/grid](https://github.com/hootsuite/grid) | Drag and drop library for two-dimensional, resizable and responsive lists. | ![GitHub](https://img.shields.io/github/stars/hootsuite/grid) |
| [jquery-match-height](https://github.com/liabru/jquery-match-height) | [liabru/jquery-match-height](https://github.com/liabru/jquery-match-height) | a responsive equal heights plugin for jQuery. | ![GitHub](https://img.shields.io/github/stars/liabru/jquery-match-height) |
| [SurveyJS](https://github.com/surveyjs/survey-library) | [surveyjs/survey-library](https://github.com/surveyjs/survey-library) | SurveyJS is a JavaScript Survey and Form Library. https://surveyjs.io/ | ![GitHub](https://img.shields.io/github/stars/surveyjs/survey-library) |
| [Array Explorer](https://github.com/sdras/array-explorer) | [sdras/array-explorer](https://github.com/sdras/array-explorer) | and [Object Explorer](https://objectexplorer.netlify.app/) - Resources to help figure out what native JavaScript method would be best to use at any given time. | ![GitHub](https://img.shields.io/github/stars/sdras/array-explorer) |
| [Clipboard.js](https://clipboardjs.com/) | - | "Copy to clipboard" without Flash or use of Frameworks. |  |
| [ky](https://github.com/sindresorhus/ky) | [sindresorhus/ky](https://github.com/sindresorhus/ky) | Tiny and elegant HTTP client based on the browser Fetch API. | ![GitHub](https://img.shields.io/github/stars/sindresorhus/ky) |
| [Fcal](https://github.com/5anthosh/fcal) | [5anthosh/fcal](https://github.com/5anthosh/fcal) | Math expression evaluator. | ![GitHub](https://img.shields.io/github/stars/5anthosh/fcal) |
| [emoji-button](https://github.com/joeattardi/emoji-button) | [joeattardi/emoji-button](https://github.com/joeattardi/emoji-button) | Vanilla JavaScript emoji picker component. | ![GitHub](https://img.shields.io/github/stars/joeattardi/emoji-button) |
| [iooxa](https://github.com/iooxa/article) | [iooxa/article](https://github.com/iooxa/article) | Components for interactive scientific writing, reactive documents and explorable explanations. | ![GitHub](https://img.shields.io/github/stars/iooxa/article) |
| [Idyll](https://github.com/idyll-lang/idyll) | [idyll-lang/idyll](https://github.com/idyll-lang/idyll) | Create explorable explanations and interactive storytelling essays. Can be [embedded in HTML](https://github.com/idyll-lang/idyll-embed). | ![GitHub](https://img.shields.io/github/stars/idyll-lang/idyll) |
| [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) | [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) | Algorithms and data structures implemented in JavaScript with explanations and links to further readings. | ![GitHub](https://img.shields.io/github/stars/trekhleb/javascript-algorithms) |
| [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) | [fingerprintjs/fingerprintjs](https://github.com/fingerprintjs/fingerprintjs) | Makes a visitor identifier from a browser fingerprint that stays the same in incognito mode and when browser data is purged. | ![GitHub](https://img.shields.io/github/stars/fingerprintjs/fingerprintjs) |
| [Peg.js](https://github.com/pegjs/pegjs) | [pegjs/pegjs](https://github.com/pegjs/pegjs) | A simple parser generator for JavaScript that produces fast parsers with excellent error reporting. Usable from your browser, from the command line, or via JavaScript API. | ![GitHub](https://img.shields.io/github/stars/pegjs/pegjs) |
| [lune](https://github.com/ryanseys/lune) | [ryanseys/lune](https://github.com/ryanseys/lune) | Library to calculate the phases of the moon accurately. | ![GitHub](https://img.shields.io/github/stars/ryanseys/lune) |
| [jsemu](https://github.com/fcambus/jsemu) | [fcambus/jsemu](https://github.com/fcambus/jsemu) | A list of emulators written in the JavaScript programming language. | ![GitHub](https://img.shields.io/github/stars/fcambus/jsemu) |


## Worth Reading
 
| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) | [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) | Possibly the best book written on modern JavaScript, completely readable online for free, or can be bought to support the author. | ![GitHub](https://img.shields.io/github/stars/getify/You-Dont-Know-JS) |
| [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) | [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way) | An easy-to-read, quick reference for JS best practices, accepted coding standards, and links around the Web. | ![GitHub](https://img.shields.io/github/stars/braziljs/js-the-right-way) |
| [JSbooks](https://github.com/revolunet/JSbooks) | [revolunet/JSbooks](https://github.com/revolunet/JSbooks) | Directory of free JavaScript ebooks. | ![GitHub](https://img.shields.io/github/stars/revolunet/JSbooks) |
| [Superhero.js](http://superherojs.com) | - | A collection of resources about creating, testing and maintaining a large JavaScript code base. |  |
| [SJSJ](https://github.com/KittyGiraudel/SJSJ) | [KittyGiraudel/SJSJ](https://github.com/KittyGiraudel/SJSJ) | Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words. | ![GitHub](https://img.shields.io/github/stars/KittyGiraudel/SJSJ) |
| [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) | [sarbbottam/write-an-open-source-js-lib](https://github.com/sarbbottam/write-an-open-source-js-lib) | A comprehensive guide through a set of steps to publish a JavaScript open source library. | ![GitHub](https://img.shields.io/github/stars/sarbbottam/write-an-open-source-js-lib) |
| [JavaScript Tutorials](https://hackr.io/tutorials/learn-javascript) | - | Learn Javascript online from a diverse range of user ranked online tutorials. |  |
| [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) | [getify/Functional-Light-JS](https://github.com/getify/Functional-Light-JS) | Pragmatic, balanced FP in JavaScript. | ![GitHub](https://img.shields.io/github/stars/getify/Functional-Light-JS) |
| [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) | [ryanmcdermott/clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript) | Clean Code concepts adapted for JavaScript. | ![GitHub](https://img.shields.io/github/stars/ryanmcdermott/clean-code-javascript) |
| [Roadmap.sh JavaScript Roadmap](https://roadmap.sh/javascript) | - | Learn JavaScript from a community sourced learning roadmap. |  |


## Other Awesome Lists
 
| Name | Repository | Description | Badges |
|:-----|:-----------|:------------|:-------|
| [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css) | [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css) |  | ![GitHub](https://img.shields.io/github/stars/sotayamashita/awesome-css) |
| [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) | [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) |  | ![GitHub](https://img.shields.io/github/stars/emijrp/awesome-awesome) |
| [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) |  | ![GitHub](https://img.shields.io/github/stars/bayandin/awesome-awesomeness) |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | [sindresorhus/awesome](https://github.com/sindresorhus/awesome) |  | ![GitHub](https://img.shields.io/github/stars/sindresorhus/awesome) |
| [jnv/list](https://github.com/jnv/lists) | [jnv/lists](https://github.com/jnv/lists) |  | ![GitHub](https://img.shields.io/github/stars/jnv/lists) |
| [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs) | [gianarb/awesome-angularjs](https://github.com/gianarb/awesome-angularjs) |  | ![GitHub](https://img.shields.io/github/stars/gianarb/awesome-angularjs) |
| [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo) | [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo) |  | ![GitHub](https://img.shields.io/github/stars/peterkokot/awesome-dojo) |
| [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) | [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) |  | ![GitHub](https://img.shields.io/github/stars/addyosmani/es6-tools) |
| [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning) | [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning) |  | ![GitHub](https://img.shields.io/github/stars/ericdouglas/ES6-Learning) |
| [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents) | [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents) |  | ![GitHub](https://img.shields.io/github/stars/obetomuniz/awesome-webcomponents) |
| [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) | [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) |  | ![GitHub](https://img.shields.io/github/stars/willianjusten/awesome-svg) |
| [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) | [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) |  | ![GitHub](https://img.shields.io/github/stars/davidsonfellipe/awesome-wpo) |
| [instanceofpro/awesome-backbone](https://github.com/sadcitizen/awesome-backbone) | [sadcitizen/awesome-backbone](https://github.com/sadcitizen/awesome-backbone) |  | ![GitHub](https://img.shields.io/github/stars/sadcitizen/awesome-backbone) |
| [enaqx/awesome-react](https://github.com/enaqx/awesome-react) | [enaqx/awesome-react](https://github.com/enaqx/awesome-react) |  | ![GitHub](https://img.shields.io/github/stars/enaqx/awesome-react) |
| [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch) | [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch) |  | ![GitHub](https://img.shields.io/github/stars/bolshchikov/js-must-watch) |
| [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery) | [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery) |  | ![GitHub](https://img.shields.io/github/stars/peterkokot/awesome-jquery) |
| [davidyezsetz/you-might-not-need-jquery-plugins](https://github.com/davidyezsetz/you-might-not-need-jquery-plugins) | [davidyezsetz/you-might-not-need-jquery-plugins](https://github.com/davidyezsetz/you-might-not-need-jquery-plugins) |  | ![GitHub](https://img.shields.io/github/stars/davidyezsetz/you-might-not-need-jquery-plugins) |
| [MaximAbramchuck/awesome-interviews](https://github.com/MaximAbramchuck/awesome-interview-questions) | [MaximAbramchuck/awesome-interview-questions](https://github.com/MaximAbramchuck/awesome-interview-questions) |  | ![GitHub](https://img.shields.io/github/stars/MaximAbramchuck/awesome-interview-questions) |
| [denolib/awesome-deno](https://github.com/denolib/awesome-deno) | [denolib/awesome-deno](https://github.com/denolib/awesome-deno) |  | ![GitHub](https://img.shields.io/github/stars/denolib/awesome-deno) |
| [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun) | [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun) |  | ![GitHub](https://img.shields.io/github/stars/apvarun/awesome-bun) |


## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.
