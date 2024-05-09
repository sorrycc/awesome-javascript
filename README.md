# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sorrycc/awesome-javascript/)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
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
    * [Image](#image)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [Generators](#generators)
  * [Full Text Search](#full-text-search)
  * [SDK](#sdk)
  * [Misc](#misc)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----

## Package Managers
*Host the JavaScript libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - npm is the package manager for JavaScript.
* [Bower](https://github.com/bower/bower) - A package manager for the web.
* [component](https://github.com/componentjs/component) - Client package management for building better web applications.
* [spm](https://github.com/spmjs/spm) - Brand new static package manager.
* [jam](https://github.com/caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository.
* [jspm](https://github.com/jspm/jspm-cli) - Frictionless browser package management.
* [Ender](https://github.com/ender-js/Ender) - The no-library library.
* [volo](https://github.com/volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects.
* [Duo](https://github.com/duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.
* [pnpm](https://pnpm.io/) - Fast, disk space efficient package manager.

## Component Management

* [Bit](https://github.com/teambit/bit) - Create, find and reuse components (React, Angular, Node etc.) across applications.

## Loaders
*Module or loading system for JavaScript.*

* [RequireJS](https://github.com/requirejs/requirejs) - A file and module loader for JavaScript.
* [browserify](https://github.com/substack/node-browserify) - Browser-side require() the node.js way.
* [SeaJS](https://github.com/seajs/seajs) - A Module Loader for the Web.
* [HeadJS](https://github.com/headjs/headjs) - The only script in your HEAD.
* [lazyload](https://github.com/rgrove/lazyload/) - Tiny, dependency-free async JavaScript and CSS loader.
* [script.js](https://github.com/ded/script.js) - Asynchronous JavaScript loader and dependency manager.
* [systemjs](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader.
* [LodJS](https://github.com/yanhaijing/lodjs) - Module loader based on AMD.
* [ESL](https://github.com/ecomfe/esl) - Module loader browser first, support lazy define and AMD.
* [modulejs](https://github.com/lrsjng/modulejs) - Lightweight JavaScript module system.

## Transpilers
*Software that converts the modern JavaScript syntax into the older JavaScript syntax.*

* [SWC](https://swc.rs/) - Extensible Rust-based platform for compilation.

## Bundlers

* [webpack](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser.
* [Rollup](https://github.com/rollup/rollup) - Next-generation ES6 module bundler.
* [Brunch](https://github.com/brunch/brunch) - Fast front-end web app build tool with simple declarative config.
* [Parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero configuration web application bundler.
* [Microbundle](https://github.com/developit/microbundle) - Zero-configuration bundler for tiny modules.
* [FuseBox](https://github.com/fuse-box/fuse-box) - A bundler that does it right
* [Snowpack](https://www.snowpack.dev/) - A lightning-fast frontend build tool, designed for the modern web.

# Minimizers

* [Terser](https://github.com/terser/terser) - parser, mangler and compressor toolkit for ES6+
* [Uglify](https://github.com/mishoo/UglifyJS) - parser / mangler / compressor / beautifier toolkit

## Type Checkers

* [TypeScript](https://www.typescriptlang.org/) - A typed superset of JavaScript that compiles to plain JavaScript.
* [Flow.js](https://flow.org/) - A static type checker for JavaScript from Facebook.
* [Hegel](https://hegel.js.org/) -  A static type checker for JavaScript with a bias on type inference an strong type system.
* [TypL](https://github.com/getify/TypL) - the JavaScript Type Linter with a bias on type inference.
* [Hindley Milner Definitions](https://github.com/xodio/hm-def) - runtime type checking for JavaScript functions using Haskell-alike Hindley Milner type signatures.

## Testing Frameworks

### Frameworks

* [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun JavaScript test framework for node.js & the browser.
* [jasmine](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework.
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* [jest](https://github.com/facebook/jest) - Painless JavaScript Unit Testing.
* [prova](https://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify
* [DalekJS](https://github.com/dalekjs/dalek) - Automated cross browser functional testing with JavaScript
* [Protractor](https://github.com/angular/protractor) - Protractor is an end-to-end test framework for AngularJS applications.
* [tape](https://github.com/substack/tape) - Tap-producing test harness for node and browsers.
* [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
* [ava](https://github.com/avajs/ava) - 🚀 Futuristic JavaScript test runner
* [Cypress](https://www.cypress.io/) - Complete end-to-end testing framework for anything that runs in a browser and beyond.

### Assertion

* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [Enzyme](https://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [react testing library](https://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
* [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript.
* [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.
* [proxyquire](https://github.com/thlorenz/proxyquire) - Stub nodejs's require.

### Coverage

* [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool.
* [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for JavaScript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner

* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* [casperjs](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [totoro](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool.
* [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript.
* [nightwatch](https://github.com/nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.
* [puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Chrome Node.js API by official Google Chrome team.
* [webdriverio](https://github.com/webdriverio/webdriverio) - Next-gen WebDriver test automation framework for Node.js.
* [taiko](https://github.com/getgauge/taiko) - A Node.js library with a simple API to automate Chromium based browsers.
* [Playwright](https://github.com/microsoft/playwright) - Node.js library to automate Chromium, Firefox and WebKit with a single API.

## QA Tools

* [prettier](https://github.com/prettier/prettier) - Prettier is an opinionated code formatter.
* [JSHint](https://github.com/jshint/jshint/) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
* [jsfmt](https://github.com/rdio/jsfmt) - For formatting, searching, and rewriting JavaScript.
* [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
* [buddy.js](https://github.com/danielstjules/buddy.js) - Magic number detection for JavaScript.
* [ESLint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript.
* [JSLint](https://github.com/douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language.
* [JavaScript Standard Style](https://github.com/feross/standard) - Opinionated, no-configuration style guide, style checker, and formatter
* [Pre-evaluate code at buildtime](https://github.com/kentcdodds/preval.macro) - Pre-evaluate your front end javascript code at build-time
* [JS-Beautifier](https://github.com/beautify-web/js-beautify) - Npm cli and library to format JS code.
* [husky](https://github.com/typicode/husky) - Prevents bad git commit, git push and more.

## MVC Frameworks and Libraries

* [angular.js](https://github.com/angular/angular.js) - HTML enhanced for web apps. (deprecated)
* [angular](https://github.com/angular/angular) - Angular is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.
* [aurelia](http://aurelia.io) - A JavaScript client framework for mobile, desktop and web.
* [backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events.
* [ember.js](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications.
* [meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-javascript web framework.
* [ractive](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation.
* [vue](https://github.com/vuejs/vue) - Intuitive, fast & composable MVVM for building interactive interfaces.
* [svelte](https://github.com/sveltejs/svelte) - Svelte is a new way to build web applications. It's a compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.
* [knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* [spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications.
* [espresso.js](https://github.com/techlayer/espresso.js) - A minimal JavaScript library for crafting user interfaces.
* [canjs](https://github.com/canjs/canjs) - Can do JS, better, faster, easier.
* [react](https://reactjs.org/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [hyperapp](https://github.com/hyperapp/hyperapp) - 1kb JavaScript library for building frontend applications.
* [preact](https://github.com/developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.
* [nativescript](https://github.com/NativeScript/NativeScript) - Build truly native cross-platform iOS and Android apps with JavaScript.
* [react-native](https://github.com/facebook/react-native) - A framework for building native apps with React.
* [riot](https://github.com/riot/riot) - React-like library, but with very small size.
* [thorax](https://github.com/walmartlabs/thorax) - Strengthening your Backbone.
* [chaplin](https://github.com/chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library.
* [marionette](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* [ripple](https://github.com/ripplejs/ripple) - A tiny foundation for building reactive views.
* [rivets](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution.
* [derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * [derby-awesome](https://github.com/russll/awesome-derby) - A collection of awesome derby components
* [way.js](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding.
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).
* [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks is better MV-ish framework.
* [feathers](https://github.com/feathersjs/feathers) - A minimalist real-time JavaScript framework for tomorrow's apps.
* [Keo](https://github.com/Wildhoney/Keo) - Functional stateless React components with Shadow DOM support.
* [atvjs](https://github.com/emadalam/atvjs) - Blazing fast Apple TV application development using pure JavaScript.
* [Alpine.js](https://github.com/alpinejs/alpine) - offers you the reactive and declarative nature of big frameworks like Vue or React at a much lower cost.
* [inferno](https://github.com/infernojs/inferno) - 🔥 An extremely fast, React-like JavaScript library for building modern user interfaces.
* [FoalTS](https://foalts.org) - Elegant and all-inclusive Node.JS framework for building web applications (TypeScript).
* [Lucia](https://github.com/aidenybai/lucia) - 3kb library for tiny web apps.
* [Adonis](https://github.com/adonisjs/core) - The Node.js Framework highly focused on developer ergonomics, stability and confidence.
* [GrapesJS](https://github.com/artf/grapesjs) - Free and Open source Web Builder Framework. Next generation tool for building templates without coding.
* [Rete.js](https://github.com/retejs/rete) - A modular framework for visual programming allows to create node based editor in browser.
* [litegraph.js](https://github.com/jagenjo/litegraph.js) - A graph node engine and editor similar to PD or UDK Blueprints, comes with its own editor in HTML5 Canvas2D.
* [Drawflow](https://github.com/jerosoler/Drawflow) - This allow you to create data flows easily and quickly.
* [Blockly](https://github.com/google/blockly) - A library that adds a visual code editor to web and mobile apps by Google.
* [Million](https://github.com/aidenybai/million) - <1kb compiler-focused virtual DOM. It's fast!
* [Whatsup](https://github.com/whatsup/whatsup) - A frontend framework for chillout-mode development 🥤. JSX components on generators, fast mobx-like state management and exclusive cssx style system.
* [Ziko.js](https://github.com/zakarialaoui10/ziko.js) - A versatile JavaScript library offering a rich set of UI components, advanced mathematical utilities,Reactivity,animations,client side routing and graphics capabilities.

## Node-Powered CMS Frameworks

* [KeystoneJS](https://github.com/keystonejs/keystone) - powerful CMS and web app framework.
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - reactive CMS, real-time architecture and design.
* [Ghost](https://github.com/tryghost/Ghost) - simple, powerful publishing platform.
* [Apostrophe](https://github.com/punkave/apostrophe) - CMS with content editing and essential services.
* [We.js](https://github.com/wejs/we/) - framework for real time apps, sites or blogs.
* [Hatch.js](https://github.com/inventures/hatchjs) - CMS platform with social features.
* [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) - fast and minimalist CMS based on Node.js.
* [Nodizecms](https://github.com/nodize/nodizecms) - CMS for CoffeeScript lovers.
* [Cody](https://github.com/jcoppieters/cody) - CMS with WSYWYG editor.
* [PencilBlue](https://github.com/pencilblue/pencilblue/) - CMS and blogging platform.
* [Strapi](https://github.com/strapi/strapi) - Open source Node.js Headless CMS to easily build customisable APIs.
* [Factor](https://github.com/fiction-com/factor) - The Javascript CMS

## Templating Engines
*Templating engines allow you to perform string interpolation.*

* [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
* [handlebars.js](https://github.com/handlebars-lang/handlebars.js) - An extension to the Mustache templating language.
* [nunjucks](https://mozilla.github.io/nunjucks/) - A rich and powerful templating language for JavaScript from Mozilla.
* [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language.
* [doT](https://github.com/olado/doT) - The fastest + concise JavaScript template engine for nodejs and browsers.
* [dustjs](https://github.com/linkedin/dustjs/) - Asynchronous templates for the browser and node.js.
* [eco](https://github.com/sstephenson/eco/) - Embedded CoffeeScript templates.
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies.
* [t.js](https://github.com/jasonmoo/t.js) - A tiny JavaScript templating framework in ~400 bytes gzipped.
* [Pug](https://github.com/pugjs/pug) - Robust, elegant, feature rich template engine for nodejs. (formerly known as Jade)
* [EJS](https://github.com/mde/ejs) - Effective JavaScript templating.
* [xtemplate](https://github.com/xtemplate/xtemplate) - eXtensible Template Engine lib for node and the browser
* [marko](https://github.com/marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output.
* [swig](https://github.com/paularmstrong/swig) - (Archived) A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.

## Game Engines
* [A-Frame](https://aframe.io) - Make WebVR.
* [Cocos](https://www.cocos.com) - Open Source Cross-Platform Game Development Framework.
* [Impact](https://impactjs.com) - Impact - HTML5 Canvas & JavaScript Game Engine.
* [GDevelop](https://gdevelop.io) - Free and Easy Game-Making App.
* [Kaboom.js](https://kaboomjs.com) - A game programming library that helps you make games fast and fun.
* [Matter.js](https://brm.io/matter-js) - A 2D rigid body JavaScript physics engine.
* [melonJS](https://melonjs.org) - Open source HTML5 game engine that empowers developers and designers to focus on content.
* [Phaser](https://phaser.io) - Phaser - A fast, fun and free open source HTML5 game framework.
* [PixiJS](https://pixijs.com) - The HTML5 Creation Engine.
* [PlayCanvas](https://playcanvas.com) - PlayCanvas WebGL Game Engine.

## Articles and Posts

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-voc%C3%AA-deveria-conhecer-b70e94d1d706) - Article about concepts of JavaScript Functional.
* [Multi-threading using web-workers](https://www.loginradius.com/blog/async/adding-multi-threading-to-javascript-using-web-workers/) - Web Workers: Adding Multi-threading to JavaScript
* [this keyword in JavaScript](https://www.loginradius.com/blog/async/breaking-down-this-keyword-in-javascript/) - Breaking down the 'this' keyword in JavaScript

## Data Visualization
*Data visualization tools for the web.*

* [d3](https://github.com/d3/d3) - A JavaScript visualization library for HTML and SVG.
* [metrics-graphics](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts.
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library.
* [Chart.js](https://github.com/chartjs/Chart.js) - Simple HTML5 Charts using the &lt;canvas&gt; tag.
* [paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* [fabric.js](https://github.com/kangax/fabric.js) - JavaScript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* [peity](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts.
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library.
* [echarts](https://github.com/apache/echarts) - Enterprise Charts.
* [visjs](https://github.com/visjs) - Multiple Libraries for dynamic, browser-based data visualization.
* [two.js](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web.
* [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) - Charts for Raphaël.
* [sigma.js](https://github.com/jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing.
* [arbor](https://github.com/samizdatco/arbor) - A graph visualization library using web workers and jQuery.
* [cubism](https://github.com/square/cubism) - A D3 plugin for visualizing time series.
* [dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [vega](https://github.com/trifacta/vega) - A visualization grammar.
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) - Dynamic HTML5 visualization.
* [rickshaw](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs.
* [flot](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery.
* [morris.js](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs.
* [nvd3](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js.
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG.
* [heatmap.js](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps.
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - A plugin for the jQuery JavaScript library to generate small sparkline charts directly in the browser.
* [trianglify](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js.
* [d3-cloud](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript.
* [d4](https://github.com/heavysixer/d4) - A friendly reusable charts DSL for D3.
* [dimple.js](http://dimplejs.org) - Easy charts for business analytics powered by d3.
* [chartist-js](https://github.com/gionkunz/chartist-js) - Simple responsive charts.
* [epoch](https://github.com/epochjs/epoch) - A general purpose real-time charting library.
* [c3](https://github.com/c3js/c3) - D3-based reusable chart library.
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL.
* [recharts](https://github.com/recharts/recharts) - Redefined chart library built with React and D3.
* [GraphicsJS](https://github.com/AnyChart/GraphicsJS) - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.
* [mxGraph](https://github.com/jgraph/mxgraph) - Diagramming library that enables interactive graph and charting applications to be quickly created that run natively in any major browser that is supported by its vendor.
* [Frappe Charts](https://github.com/frappe/charts) - GitHub-inspired simple and modern SVG charts for the web with zero dependencies.
* [Frappe Gantt](https://github.com/frappe/gantt) - A simple, interactive, modern gantt chart library for the web.
* [G2](https://github.com/antvis/G2) - A highly interactive data-driven visualization grammar for statistical charts.
* [G2Plot](https://github.com/antvis/G2Plot) - An interactive and responsive charting library. Based on the grammar of graphics.
* [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - A fully featured graph theory library.
* [cola.js](https://ialab.it.monash.edu/webcola/) - library for arranging your HTML5 documents and diagrams using constraint-based optimization techniques
* [jointjs](https://github.com/clientIO/joint) - Diagramming library to create static diagrams or fully interactive diagramming tools.
* [vizzu](https://github.com/vizzuhq/vizzu-lib) - Library for animated data visualizations and data stories.

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](https://www.anychart.com/), [plotly](https://plotly.com/), and [lightning chart](https://www.arction.com/lightningchart-js/).

## Timeline

* [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) - A Storytelling Timeline built in JavaScript.
* [timesheet.js](https://github.com/sbstjn/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets.

## Spreadsheet

* [HANDSONTABLE](https://github.com/handsontable/handsontable) - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers
* [Frappe Datatable](https://github.com/frappe/datatable) - Frappe DataTable is a simple, modern and interactive datatable library for displaying tabular data.
* [Luckysheet](https://github.com/mengshukeji/Luckysheet) - Luckysheet is an online spreadsheet like excel that is powerful, simple to configure, and completely open source.
 * [Jspreadsheet CE](https://github.com/jspreadsheet/ce) - Jspreadsheet is a lightweight vanilla javascript plugin to create amazing web-based interactive tables and spreadsheets compatible with other spreadsheet software.

## Editors

* [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor).
* [CodeMirror](https://github.com/codemirror/CodeMirror) - In-browser code editor.
* [esprima](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis.
* [quill](https://github.com/quilljs/quill) - A cross browser rich text editor with an API.
* [medium-editor](https://github.com/yabwe/medium-editor) - Medium.com WYSIWYG editor clone.
* [pen](https://github.com/sofish/pen) - enjoy live editing (+markdown).
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium.
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor.
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - The best web text editor for everyone.
* [editor](https://github.com/lepture/editor) - A markdown editor. still on development.
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* [jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON.
* [vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent `~/.vimrc`.
* [Squire](https://github.com/neilj/Squire) - HTML5 rich text editor.
* [TinyMCE](https://github.com/tinymce/tinymce) - The JavaScript Rich Text editor.
* [trix](https://github.com/basecamp/trix) - A rich text editor for everyday writing. By Basecamp.
* [Trumbowyg](https://github.com/Alex-D/Trumbowyg) - A lightweight and amazing WYSIWYG JavaScript editor.
* [Draft.js](https://github.com/facebook/draft-js) - A React framework for building text editors.
* [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) - Simple, beautiful wysiwyg editor
* [wysihtml5](https://github.com/xing/wysihtml5) - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles.
* [raptor-editor](https://github.com/PANmedia/raptor-editor) - Raptor, an HTML5 WYSIWYG content editor!
* [popline](https://github.com/kenshin54/popline) - Popline is an HTML5 Rich-Text-Editor Toolbar.
* [Summernote](https://github.com/summernote/summernote) - Super simple WYSIWYG editor.
* [Everright-formEditor](https://github.com/Liberty-liu/Everright-formEditor) - A visual drag-and-drop low-code form editor

## Documentation

* [DevDocs](https://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [docco](http://ashkenas.com/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* [Ronn](https://github.com/rtomayko/ronn) builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web.
* [dox](https://github.com/tj/dox) is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags.
* [jsdox](https://github.com/sutoiku/jsdox) is a JSDoc3 to Markdown documentation generator.
* [ESDoc](https://github.com/esdoc/esdoc) is a good documentation generator for JavaScript.
* [YUIDoc](http://yui.github.io/yuidoc/) is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [Beautiful docs](https://github.com/beautiful-docs/beautiful-docs) is a documentation viewer based on markdown files.
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
* [jsduck](https://github.com/senchalabs/jsduck) - API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too.
* [codecrumbs](https://github.com/Bogdan-Lyashenko/codecrumbs) is a visual tool for learning and documenting a codebase by putting breadcrumbs in source code.

## Files
*Libraries for working with files.*

* [Papa Parse](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* [jBinary](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.
* [diff2html](https://github.com/rtfpessoa/diff2html) - Git diff output parser and pretty HTML generator.
* [jsPDF](https://github.com/MrRio/jsPDF) - JavaScript PDF generation.
* [PDF.js](https://github.com/mozilla/pdf.js) - PDF Reader in JavaScript.

## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* [underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt.
* [lodash](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras.
* [Sugar](https://github.com/andrewplummer/Sugar) - A JavaScript library for working with native objects.
* [lazy.js](https://github.com/dtao/lazy.js) - Like Underscore, but lazier.
* [ramda](https://github.com/ramda/ramda) - A practical functional library for JavaScript programmers.
* [mout](https://github.com/mout/mout) - Modular JavaScript Utilities.
* [preludejs](https://github.com/alanrsoares/prelude-js) - Hardcore Functional Programming for JavaScript.
* [rambda](https://github.com/selfrefactor/rambda) - Faster and smaller alternative to *Ramda*.
* [fxts](https://github.com/marpple/FxTS) - Lazy evaluation and concurrency.
* [wild-wild-path](https://github.com/ehmicky/wild-wild-path) - Object property paths with wildcards and regexps.
* [sweet-monads](https://github.com/JSMonk/sweet-monads) - A utility library containing popular monads and lazy iterators.

## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJS](https://github.com/ReactiveX/rxjs) - A reactive programming library for JavaScript.
* [Bacon](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for JavaScript.
* [Kefir](https://github.com/pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption.
* [Highland](https://caolan.github.io/highland/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* [Most.js](https://github.com/cujojs/most) - high performance FRP library.
* [MobX](https://github.com/mobxjs/mobx) - TFRP library for simple, scalable state management.
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.
* [concent](https://github.com/concentjs/concent) - Definitely the ❤️ simplest but ⚡️ strongest state management for react, it is predictable、progressive and efficient.

## Data Structure
*Data structure libraries to build a more sophisticated application.*

* [immutable-js](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector.
* [mori](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [buckets](https://github.com/mauriciosantos/Buckets-JS) - A complete, fully tested and documented data structure library written in JavaScript.
* [hashmap](https://github.com/flesler/hashmap) - Simple hashmap implementation that supports any kind of keys.
* [ngraph.graph](https://github.com/anvaka/ngraph.graph) - Graph data structure in javascript.
* [js-sdsl](https://github.com/zly201/js-sdsl) - Refer to the javascript standard data structure library implemented by c++ stl, which supports c++ bidirectional iterator mode.

## Date
*Date Libraries.*

* [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in JavaScript.
* [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js.
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* [timezone-js](https://github.com/mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data.
* [date](https://github.com/MatthewMueller/date) - Date() for humans.
* [ms.js](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
* [countdown.js](https://github.com/gumroad/countdown.js) - Super simple countdowns.
* [timeago.js](https://github.com/hustcc/timeago.js) - Simple library (less then 2kb) used to format date with `*** time ago` statement.
* [fecha](https://github.com/taylorhakes/fecha) - Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js.
* [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library.
* [map-countdown](https://github.com/dawidjaniga/map-countdown) - A browser countdown built on top of the Google Maps.
* [dayjs](https://github.com/iamkun/dayjs) - Day.js 2KB immutable date library alternative to Moment.js with the same modern API.
* [luxon](https://github.com/moment/luxon) - Luxon is a library for working with dates and times in JavaScript.

## String
*String Libraries.*

* [voca](https://github.com/panzerdp/voca) - The ultimate JavaScript string library
* [selecting](https://github.com/EvandroLG/selecting) - A library that allows you to access the text selected by the user.
* [underscore.string](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js JavaScript library.
* [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods.
* [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
* [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
* [URI.js](https://github.com/medialize/URI.js/) - JavaScript URL mutation library.
* [jsurl](https://github.com/Mikhus/domurl) - Lightweight URL manipulation with JavaScript.
* [sprintf.js](https://github.com/alexei/sprintf.js) - A sprintf implementation.
* [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings.
* [plexis](https://github.com/plexis-js/plexis) - Lo-fi, powerful, community-driven string manipulation library.
* [url-state-machine](https://github.com/anonrig/url-js) - Super fast spec-compliant URL parser state machine for Node.js.

## Number

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - A JavaScript library for formatting and manipulating numbers.
* [chance.js](https://github.com/chancejs/chancejs) - Random generator helper in JavaScript. Can generate numbers, strings etc.
* [odometer](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease.
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) JavaScript currency conversion library, for web & nodeJS.
* [Fraction.js](https://github.com/infusion/Fraction.js) - A rational number library for JavaScript.
* [Complex.js](https://github.com/infusion/Complex.js) - A complex number library for JavaScript.
* [Polynomial.js](https://github.com/infusion/Polynomial.js) - A polynomials library for JavaScript.
* [Quaternion.js](https://github.com/infusion/Quaternion.js) - A quaternion library for JavaScript

## Storage

* [store.js](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood.
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* [jStorage](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side.
* [cross-storage](https://github.com/zendesk/cross-storage) - Cross domain local storage, with permissions.
* [basket.js](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage.
* [bag.js](https://github.com/nodeca/bag.js) - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support.
* [basil.js](https://github.com/Wisembly/basil.js) - The missing JavaScript smart persistent layer.
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* [js-cookie](https://github.com/js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling browser cookies.
* [Cookies](https://github.com/ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library.
* [DB.js](https://github.com/aaronpowell/db.js/) - Promise based IndexDB Wrapper library.
* [lawnchair.js](https://github.com/brianleroux/lawnchair/) - Simple client-side JSON storage.
* [sql.js](https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten.
* [pouchdb](https://github.com/pouchdb/pouchdb) - Javascript db inspired by Apache CouchDB to run well within the browser.
* [crumbsjs](https://github.com/nirtz89/crumbsjs) - A lightweight vanilla ES6 cookies and local storage JavaScript library.
* [awesome-web-storage](https://github.com/softvar/awesome-web-storage) - Everything you need to know about client-side storage.
* [datavore](https://github.com/StanfordHCI/datavore) - A small, fast, in-browser database engine written in JavaScript.
* [Hoodie](https://github.com/hoodiehq/hoodie) - Offline First backend to work in browser without internet connectivity.
* [NeDB](https://github.com/louischatriot/nedb) - Embedded Persistent database for Browsers, nw.js, electron.
* [Lovefield](https://google.github.io/lovefield) - Lovefield is a relational database for web apps, By Google.
* [Dexie.js](https://github.com/dexie/Dexie.js) - Dexie.js is a wrapper library for indexedDB.
* [proxy-web-storage](https://github.com/KID-joker/proxy-web-storage) - Keep the type of storage value unchanged and change array and object directly. Supports listening to the changes and setting expires.

## Color

* [randomColor](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript.
* [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations.
* [color](https://github.com/Qix-/color) - JavaScript color conversion and manipulation library.
* [colors](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web.
* [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.
* [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
* [Vibrant.js](https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image.

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next](https://github.com/i18next/i18next) - internationalisation (i18n) with JavaScript the easy way.
* [polyglot](https://github.com/airbnb/polyglot.js) - tiny i18n helper library.
* [babelfish](https://github.com/nodeca/babelfish/) - i18n with human friendly API and built in plurals support.
* [ttag](https://github.com/ttag-org/ttag) - Modern javascript i18n localization library based on ES6 tagged templates and the good old GNU gettext.
* [attranslate](https://github.com/fkirc/attranslate) - A JavaScript-tool for synchronizing translation-files, including JSON/YAML/XML and other formats.

## Control Flow

* [async](https://github.com/caolan/async) - Async utilities for node and the browser.
* [q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript.
* [step](https://github.com/creationix/step/) - An async control-flow library that makes stepping through logic easy.
* [contra](https://github.com/bevacqua/contra/) - Asynchronous flow control with a functional taste to it.
* [Bluebird](https://github.com/petkaantonov/bluebird/) - fully featured promise library with focus on innovative features and performance.
* [when](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies.
* [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers).
* [sporadic](https://github.com/marcoonroad/sporadic) - Composable concurrency abstractions (such as streams, coroutines and Go-like channels) on top of promises, for Node and browser engines.

## Routing

* [director](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript.
* [page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes).
* [pathjs](https://github.com/mtrpcic/pathjs) - Simple, lightweight routing for web browsers.
* [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes.
* [davis.js](https://github.com/olivernn/davis.js) - RESTful degradable JavaScript routing using pushState.
* [navaid](https://github.com/lukeed/navaid) - A navigation aid (aka, router) for the browser in 850 bytes~!

## Security

* [DOMPurify](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
* [xss-filters](https://github.com/yahoo/xss-filters) - Secure XSS Filters by Yahoo.
* [sanitize-html](https://github.com/apostrophecms/sanitize-html) - sanitize-html provides a simple HTML sanitizer with a clear API.

## Log

* [log](https://github.com/adamschwartz/log) - Console.log with style.
* [Conzole](https://github.com/Oaxoa/Conzole) - A debug panel built in JavaScript that wraps JavaScript native console object methods and functionality in a panel displayed inside the page.
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity.
* [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends.
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.

## RegExp
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](https://regexr.com/) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.

## Voice Command

* [annyang](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition.
* [voix.js](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games.

## API

* [axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js.
* [bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser.
* [amygdala](https://github.com/lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications.
* [jquery.rest](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs.
* [Rails Ranger](https://github.com/victor-am/rails-ranger) - An opinionated REST client for Ruby on Rails APIs.
* [wretch](https://github.com/elbywan/wretch) - A tiny wrapper built around fetch with an intuitive syntax.
* [Bearer.sh](https://github.com/Bearer/bearer-js) - Universal API client that supports OAuth / API Key / Basic / etc.
* [FarFetch](https://github.com/WebsiteBeaver/far-fetch) - Modern Fetch API wrapper for simplicity, with concise file uploading.
* [Optic](https://github.com/opticdev/optic) - Optic automatically documents and tests your APIs.
* [SWR](https://github.com/vercel/swr) - React Hooks library for remote data fetching.
* [React Query](https://github.com/tannerlinsley/react-query) - Hooks for fetching, caching and updating asynchronous data in React.
* [SWRV](https://github.com/Kong/swrv) - Stale-while-revalidate data fetching for Vue.
* [Vue Query](https://github.com/DamianOsipiuk/vue-query) - Hooks for fetching, caching and updating asynchronous data in Vue.

## Streaming

* [Tailor](https://github.com/zalando/tailor) - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe.

## Vision Detection

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in JavaScript via Emscripten.

## Machine Learning

* [ConvNetJS](https://github.com/karpathy/convnetjs) - Deep Learning in JavaScript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [DN2A](https://github.com/dn2a/dn2a-javascript) - Digital Neural Networks Architecture.
* [Brain.js](https://github.com/harthur/brain) - Neural networks in JavaScript.
* [Mind.js](https://github.com/stevenmiller888/mind) - A flexible neural network library.
* [Synaptic.js](https://github.com/cazala/synaptic) - Architecture-free neural network library for node.js and the browser.
* [TensorFlow.js](https://www.tensorflow.org/js/) - A JavaScript library for training and deploying ML models in the browser and on Node.js.
* [ml5.js](https://ml5js.org) - Friendly Machine Learning for the Web.
* [Synapses](https://github.com/mrdimosthenis/Synapses) - Lightweight cross-platform Neural Network library.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native JavaScript code with zero dependencies.

## Browser Detection

* [bowser](https://github.com/ded/bowser) - a browser detector.

## Operating System
* [os.js](https://github.com/os-js/OS.js) - An open-source web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more.

## Benchmark

* [benchmark.js](https://github.com/bestiejs/benchmark.js) - A benchmarking library. As used on jsPerf.com.
* [matcha](https://github.com/logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking.

## Web Worker

* [partytown](https://github.com/BuilderIO/partytown) - Relocate resource intensive third-party scripts off of the main thread and into a web worker.
* [comlink](https://github.com/GoogleChromeLabs/comlink) - Comlink is a tiny library (1.1kB), that removes the mental barrier of thinking about postMessage and hides the fact that you are working with workers.
* [greenlet](https://github.com/developit/greenlet) - Move an async function into its own thread.
* [workerize](https://github.com/developit/workerize) - Moves a module into a Web Worker, automatically reflecting exported functions as asynchronous proxies.
* [worker-dom](https://github.com/ampproject/worker-dom) - An in-progress implementation of the DOM API intended to run within a Web Worker.
* [threads.js](https://github.com/andywer/threads.js) - Offload CPU-intensive tasks to worker threads in node.js, web browsers and electron using one uniform API.
* [workly](https://github.com/pshihn/workly) - A really simple way to move a function or class to a web worker.
* [stockroom](https://github.com/developit/stockroom) - Offload your store management to a worker easily.
* [workerpool](https://github.com/josdejong/workerpool) - Offload tasks to a pool of workers on node.js and in the browser.
* [clooney](https://github.com/GoogleChromeLabs/clooney) - Clooney is an actor library for the web. Use workers without thinking about workers.

## Code highlighting

* [Highlight.js](https://github.com/isagalaev/highlight.js) - JavaScript syntax highlighter.
* [PrismJS](https://github.com/PrismJS/prism) - Lightweight, robust, elegant syntax highlighting.

## Loading Status
*Libraries for indicate load status.*

* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - Create Google Material Design progress linear bars.
* [NProgress](https://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* [Spin.js](https://github.com/fgnass/spin.js) - A spinning activity indicator.
* [progress.js](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page.
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths.
* [pace](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site.
* [topbar](https://github.com/buunguyen/topbar) - Tiny & beautiful site-wide progress indicator.
* [nanobar](https://github.com/jacoborus/nanobar) - Very lightweight progress bars. No jQuery.
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations.
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS.
* [Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators.
* [css-loaders](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS

## Validation

* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of JavaScript.
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin.
* [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization.
* [validate.js](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter.
* [validatr](https://github.com/jaymorrow/validatr/) - Cross Browser HTML5 Form Validation.
* [FormValidation](https://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.
* [is.js](https://github.com/arasatasaygin/is.js) - Check types, regexps, presence, time and more.
* [FieldVal](https://github.com/FieldVal/fieldval-js) - multipurpose validation library. Supports both sync and async validation.
* [Funval](https://github.com/neuledge/funval) - Data validation using functions interfaces (support TypeScript).
* [vest](https://github.com/ealush/vest) - 🦺 Declarative form validation framework inspired by unit testing.

## Keyboard Wrappers

* [mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in JavaScript.
* [keymaster](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts.
* [Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key.
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* [jwerty](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events.

## Tours And Guides

* [intro.js](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project.
* [shepherd](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app.
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers.
* [tourist](https://github.com/easelinc/tourist) - Simple, flexible tours for your app.
* [hopscotch](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages.
* [joyride](https://github.com/zurb/joyride) - jQuery feature tour plugin.
* [focusable](https://github.com/zzarcon/focusable) - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page.
* [driver.js](https://github.com/kamranahmedse/driver.js) - Powerful yet light-weight, vanilla JavaScript engine to drive the user's focus across the page

## Notifications

* [iziToast](https://github.com/dolce/iziToast) - Elegant, responsive, flexible and lightweight notification plugin with no dependencies.
* [messenger](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app.
* [noty](https://github.com/needim/noty) - jQuery notification plugin.
* [pnotify](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* [toastr](https://github.com/CodeSeven/toastr) - Simple JavaScript toast notifications.
* [humane-js](https://github.com/wavded/humane-js) - A simple, modern, browser notification system.
* [smoke.js](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for JavaScript.
* [notie](https://github.com/jaredreich/notie) - Simple notifications and inputs with no dependencies.
* [notifire](https://github.com/notifirehq/notifire) - Open-source notification infrastructure for products.
* [toastify-js](https://github.com/apvarun/toastify-js) - Pure JavaScript library for better notification messages.

## Sliders

* [Swiper](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions.
* [slick](https://github.com/kenwheeler/slick) - The last carousel you'll ever need.
* [slidesJs](http://www.slidesjs.com) - Is a responsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin.
* [sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* [vegas](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* [Sequence](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* [reveal.js](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML.
* [impress.js](https://github.com/impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* [bespoke.js](https://github.com/bespokejs/bespoke) - DIY Presentation Micro-Framework
* [Strut](https://github.com/tantaman/Strut) - Strut - An Impress.js and Bespoke.js Presentation Editor
* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent.
* [jcSlider](https://github.com/JoanClaret/jcSlider) - A responsive slider jQuery plugin with CSS animations.
* [basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) - Simple to use, simple to theme, simple to customise.
* [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.
* [slidr](https://github.com/bchanx/slidr) - add some slide effects.
* [Flickity](https://github.com/metafizzy/flickity) - Touch, responsive, flickable galleries.
* [Glide.js](https://github.com/jedrzejchalubek/glidejs) - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast.
* [Embla Carousel](https://github.com/davidcetinkaya/embla-carousel) - An extensible low level carousel for the web, written in TypeScript.

## Range Sliders

* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support.
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - A JavaScript slider selector that supports dates.
* [noUiSlider](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat.
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill.


## Form Widgets

### Input

* [typeahead.js](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library.
* [tag-it](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* [At.js](https://github.com/ichord/At.js) - Add GitHub like mentions autocomplete to your application.
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute.
* [fancyInput](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects.
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure JavaScript mask input.
* [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) - jQuery plugin for styling checkboxes and radio-buttons. With skin support.
* [awesomplete](https://github.com/LeaVerou/awesomplete) - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - https://projects.verou.me/awesomplete/

### Calendar

* [pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* [Pikaday](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* [fullcalendar](https://github.com/fullcalendar/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin).
* [rome](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI.
* [Date Range Picker](https://github.com/dangrossman/daterangepicker) - creates a dropdown menu from which a user can select a range of dates.
* [Duet Date Picker](https://github.com/duetds/date-picker) - open source version of Duet Design System’s accessible date picker, WCAG 2.1 accessibility complaint
* [tui.calendar](https://github.com/nhn/tui.calendar) - A JavaScript schedule calendar that is full featured. Now your service just got the customizable calendar.
* [Schedule-X](https://github.com/schedule-x/schedule-x) - Material design event calendar. Features drag & drop, dark mode, multiple views and more.

### Select

* [selectize.js](https://github.com/selectize/selectize.js) - Selectize is the hybrid of a textbox and `<select>` box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc.
* [select2](https://github.com/select2/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* [chosen](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly.

### File Uploader

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery.
* [dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* [fine-uploader](https://github.com/FineUploader/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* [FileAPI](https://github.com/mailru/FileAPI) - A set of JavaScript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [plupload](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.
* [filepond](https://github.com/pqina/filepond) - A JavaScript library that can upload anything you throw at it, optimizes images for faster uploads, and offers a great, accessible, silky smooth user experience.

### Other

* [form](https://github.com/jquery-form/form) - jQuery Form Plugin.
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted.
* [Countable](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* [card](https://github.com/jessepollak/card) - Make your credit card form better in one line of code.
* [stretchy](https://github.com/LeaVerou/stretchy) - Form element autosizing, the way it should be.
* [analytics](https://github.com/davidwells/analytics) - A lightweight, extendable analytics library designed to work with any third-party analytics provider to track page views, custom events, & identify users.
* [dat.GUI](https://github.com/dataarts/dat.gui) - A lightweight gui controller for changing variables in JavaScript.
## Tips

* [tipsy](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery.
* [opentip](https://github.com/enyo/opentip) - An open source JavaScript tooltip based on the prototype framework.
* [qTip2](https://github.com/qTip2/qTip2) - Pretty powerful tooltips.
* [tooltipster](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin.
* [simptip](https://github.com/arashmanteghi/simptip) - A simple CSS tooltip made with Sass.
* [toolbar](https://github.com/paulkinzett/toolbar) - A tooltip style toolbar jQuery plugin
* [hint.css](https://github.com/chinchang/hint.css) - A tooltip library in CSS for your lovely websites.

## Modals and Popups

* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* [jquery-popbox](https://github.com/gristmill/jquery-popbox) - jQuery PopBox UI Element.
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups.
* [vex](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style.
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* [css-modal](https://github.com/drublic/css-modal) - A modal built out of pure CSS.
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips.
* [SweetAlert](https://github.com/t4t5/sweetalert) - An awesome replacement for JavaScript's alert.
* [SweetAlert2](https://github.com/sweetalert2/sweetalert2) - An awesome replacement for JavaScript's alert.
* [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript.
* [colorbox](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery.
* [fancyBox](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* [swipebox](https://github.com/brutaldesign/swipebox) - A touchable jQuery lightbox
* [jBox](https://github.com/StephanWagner/jBox) - jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more.
* [lightGallery](https://github.com/sachinchoolur/lightGallery) - A customizable, modular, responsive, lightbox gallery plugin for jQuery.
* [keukenhof](https://github.com/Alexandrshy/keukenhof) - Lightweight, no dependencies, accessibility enabled TypeScript library for creating modal windows.
* [screenfull.js](https://github.com/sindresorhus/screenfull.js) - the JavaScript Fullscreen API, which lets you bring the page or any element into fullscreen. Smoothens out the browser implementation differences, so you don't have to.

## Scroll

* [scrollMonitor](https://github.com/stutrek/scrollMonitor) - A simple and fast API to monitor elements as you scroll.
* [headroom](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it.
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* [iscroll](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform JavaScript scroller.
* [skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* [parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device.
* [stellar.js](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy.
* [plax](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing.
* [jparallax](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect.
* [fullPage](https://github.com/alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites).
* [ScrollMenu](https://github.com/s-yadav/ScrollMenu) - A new interface to replace old boring scrollbar.
* [Clusterize.js](https://github.com/NeXTs/Clusterize.js) - Tiny vanilla JS plugin to display large data sets easily.
* [simpleParallax](https://github.com/geosigno/simpleParallax) - Simple and tiny JavaScript library to add parallax animations on any images
* [rellax](https://github.com/dixonandmoe/rellax) - Buttery smooth, super lightweight, vanilla javascript parallax library.
* [asscroll](https://github.com/ashthornton/asscroll) - A hybrid smooth scroll setup that combines the performance gains of virtual scroll with the reliability of native scroll.
* [stroll](https://github.com/hakimel/stroll.js) - A collection of CSS List scroll effects bind to dom through javascript.
* [locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) - Detects the elements in viewport and smooth scrolling with parallax.
* [elevator.js](https://github.com/tholman/elevator.js) - Finally, a "back to top" button that behaves like a real elevator.

## Menu

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* [jQuery contextMenu](https://github.com/swisnl/jQuery-contextMenu) - contextMenu manager.
* [Slideout](https://github.com/mango/slideout) - A responsive touch slideout navigation menu for mobile web apps.
* [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) - A sliding swipe menu that works with touchSwipe library.
* [mmenu](https://github.com/FrDH/jQuery.mmenu) - The best jQuery plugin for app look-alike on- and off-canvas menus with sliding submenus for your website and webapp.

## Table/Grid

* [jTable](https://github.com/hikalkan/jtable) - A jQuery plugin to create AJAX based CRUD tables.
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [Tabulator](http://olifolkerd.github.io/tabulator/) - (jQuery plug-in) An extremely flexible library that create tables with a range of interactive features from any JSON data source or existing HTML table.
* [Bootstrap Table](https://bootstrap-table.com/) - An Extension to the popular Bootstrap framework for creating tables that fit the style of your site with no need for additional markup.
* [floatThead](https://github.com/mkoryak/floatThead) - (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css.
* [Masonry](https://masonry.desandro.com/) - A cascading grid layout library.
* [Packery](https://packery.metafizzy.co/) - A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts.
* [Isotope](https://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.
* [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) - Grid based on CSS3 flexbox.

## Frameworks

* [Semantic UI](https://semantic-ui.com/) - UI Kit with lots of themes and elements.
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* [fluidity](https://github.com/mrmrs/fluidity) - The worlds smallest fully-responsive css framework.
* [Ink](https://github.com/sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping.
* [DataFormsJS](https://github.com/dataformsjs/dataformsjs) - A minimal JavaScript Framework and standalone components for rapid development of sites and SPA's.
* [EHTML](https://github.com/Guseyn/EHTML) - HTML Framework that allows you not to write JavaScript code.

## Boilerplates

 * [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites.
 * [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) - A front-end template that helps you build fast, modern mobile web apps.
 * [webplate](https://github.com/chrishumboldt/webplate) - An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use.
 * [Cerberus](https://github.com/TedGoas/Cerberus) - A few simple, but solid patterns for responsive HTML emails. Even in Outlook.
 * [full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) - An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation.
 * [Fluid-Squares](https://github.com/crozynski/Fluid-Squares) - A fluid grid of square units.
 * [Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) - An example of a mobile-first responsive web design.
 * [this-is-responsive](https://github.com/bradfrost/this-is-responsive) - This Is Responsive.
 * [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) Task automation with NPM run-scripts.
 * [Wasp](https://github.com/wasp-lang/wasp) Wasp is a declarative domain-specific language for developing, building, and deploying modern Javascript full-stack web apps with less code.

## Images

 * [Drift](https://github.com/imgix/drift) - Easily add "zoom on hover" functionality to your site's images. Lightweight, no-dependency JavaScript.
 * [Magnificent.js](https://github.com/AndersDJohnson/magnificent.js) - Zoom responsively, images & more, w/ jQuery.
 * [Panolens.js](https://github.com/pchen66/panolens.js) - Panolens.js is an event-driven and WebGL based panorama viewer. Lightweight and flexible
## Gesture

* [hammer.js](https://github.com/hammerjs/hammer.js) - A JavaScript library for multi-touch gestures.
* [touchemulator](https://github.com/hammerjs/touchemulator) - Emulate touch input on your desktop.
* [Dragula](https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts.

## Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps.
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine.
* [gmaps](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps.
* [polymaps](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* [kartograph.js](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps.
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin.
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library.
* [OpenLayers3](https://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.
* [H3js](https://github.com/uber/h3) - Hexagonal hierarchical geospatial indexing system ported to javascript by Uber for geospatial visualization.

## Video/Audio

 * [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.
 * [Play-em JS](https://github.com/adrienjoly/playemjs) - Play'em is a JavaScript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo.
 * [polyplayer](https://github.com/Acconut/polyplayer) - Rule YouTube, Soundcloud and Vimeo player with one API.
 * [flowplayer](https://github.com/flowplayer/flowplayer) - The HTML5 video player for the web
 <https://flowplayer.com/>
 * [mediaelement](https://github.com/johndyer/mediaelement) - HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://www.mediaelementjs.com/>
 * [SoundJS](https://github.com/CreateJS/SoundJS) - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers.
 * [video.js](https://github.com/videojs/video.js) - Video.js - open source HTML5 & Flash video player.
 * [FitVids.js](https://github.com/davatron5000/FitVids.js) - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
 * [Ion.Sound](https://github.com/IonDen/ion.sound) - Simple sounds on any web page.
 * [photobooth-js](https://github.com/WolframHempel/photobooth-js) - A widget that allows users to take their avatar pictures on your site.
 * [clappr](https://github.com/clappr/clappr) - An extensible media player for the web http://clappr.io
 * [exifr](https://github.com/MikeKovarik/exifr) - The fastest and most versatile EXIF reading library. https://mutiny.cz/exifr/
 * [ts-audio](https://github.com/EvandroLG/ts-audio) - an agnostic and easy-to-use library to work with the `AudioContext` API.
 * [AmplitudeJS](https://521dimensions.com/open-source/amplitudejs) - Open Source HTML5 Web Audio Library. Design your web audio player, the way you want. No dependencies required.
 * [ractive-player](https://github.com/ysulyma/ractive-player) - A library for making interactive videos in React.js.
 * [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) - FFmpeg optimized for in-browser use: minimal size for faster loading, asm.js, performance tunings, etc.
 * [flv.js](https://github.com/bilibili/flv.js) - An HTML5 Flash Video (FLV) Player written in pure JavaScript without Flash.
 * [hls.js](https://github.com/video-dev/hls.js) -  A JavaScript library that implements an HTTP Live Streaming client. It relies on HTML5 video and MediaSource Extensions for playback.

## Typography

 * [FlowType.JS](https://github.com/simplefocus/FlowType.JS) - Web typography at its finest: font-size and line-height based on element width.
 * [BigText](https://github.com/zachleat/BigText) - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width.
 * [circletype](https://github.com/peterhry/circletype) - A jQuery plugin that lets you curve type on the web.
 * [slabText](https://github.com/freqDec/slabText/) - A jQuery plugin for producing big, bold & responsive headlines.
 * [simple-text-rotator](https://github.com/peachananr/simple-text-rotator) - Add a super simple rotating text to your website with little to no markup.
 * [novacancy.js](https://github.com/chuckyglitch/novacancy.js) - Text Neon Golden effect jQuery plug-in.
 * [jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) - Make your text sizing responsive!
 * [FitText.js](https://github.com/davatron5000/FitText.js) - A jQuery plugin for inflating web type.
 * [Lettering.js](https://github.com/davatron5000/Lettering.js) - A lightweight, easy to use JavaScript `<span>` injector for radical Web Typography.

## Animations

* [velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation.
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery.
* [bounce.js](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time.
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers.
* [TransitionEnd](https://github.com/EvandroLG/transitionEnd) - TransitionEnd is an agnostic and cross-browser library to work with transitioned event.
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - JavaScript library to create physics-based CSS animations.
* [the-cube](https://github.com/pstadler/the-cube) - The Cube is an experiment with CSS3 transitions.
* [Effeckt.css](https://github.com/h5bp/Effeckt.css) - A Performant Transitions and Animations Library.
* [animate.css](https://github.com/daneden/animate.css) - A cross-browser library of CSS animations. As easy to use as an easy thing.
* [textillate](https://github.com/jschr/textillate) - A simple plugin for CSS3 text animations.
* [move.js](https://github.com/visionmedia/move.js) - CSS3 backed JavaScript animation framework.
* [animatable](https://github.com/LeaVerou/animatable) - One property, two values, endless possibilities.
* [shuffle-images](https://github.com/peachananr/shuffle-images) - The Simplest Way to shuffle through images in a Creative Way.
* [smoothState.js](https://github.com/miguel-perez/smoothState.js) - Unobtrusive page transitions with jQuery.
* [Anime.js](https://animejs.com/) - A JavaScript animation engine.
* [Mo.js](https://mojs.github.io/) - Motion graphics toolbelt for the web.
* [particles.js](https://github.com/VincentGarreau/particles.js) - A lightweight JavaScript library for creating particles.
* [tsParticles](https://github.com/matteobruni/tsparticles) - A new and improved version of particles.js with bug fixes and many new features.
* [particles-bg](https://github.com/lindelof/particles-bg) - A lightweight React particles animation background component.
* [barbajs](https://github.com/barbajs/barba) - It helps you create fluid and smooth transitions between your website's pages.
* [typicaljs](https://github.com/camwiegert/typical) - Animated typing in ~400 bytes 🐡 of JavaScript
* [AutoAnimate](https://auto-animate.formkit.com) - Add motion to your apps with a single line of code.

## Image Processing

* [lena.js](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions.
* [pica](https://github.com/nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS).
* [cropper](https://github.com/fengyuanchen/cropper) - A simple jQuery image cropping plugin.

## ES6

* [es6features](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features.
* [es6-features](https://github.com/rse/es6-features) - ECMAScript 6: Feature Overview & Comparison.
* [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets.
* [ECMAScript 6 compatibility table](https://compat-table.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* [Babel (Formerly 6to5)](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime.
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.


## Generators

* [Gatsby.js](https://github.com/gatsbyjs/gatsby) - React-based static site generator.
* [Gridsome](https://github.com/gridsome/gridsome) - Vue-powered static site generator.
* [Docusaurus](https://github.com/facebook/docusaurus) - React-based static site generator by Facebook, ideal for content-centric websites.
* [Next.js](https://github.com/vercel/next.js) - React powered static site generator, and they say "All the tools you need to make the Web. Faster.".

## SDK

* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - JavaScript SDK design guide extracted from work and personal experience.
* [Spotify SDK](https://github.com/loverajoel/spotify-sdk) - Entity oriented SDK to work with the Spotify Web API.
* [Square Node.js SDK](https://github.com/square/connect-nodejs-sdk/) - JavaScript client library for payments and other Square APIs.

## Full Text Search

* [lunr](https://github.com/olivernn/lunr.js) - Library for use in the browser and It indexes JSON documents and provides a simple search interface for retrieving documents that best match text queries.
* [flexsearch](https://github.com/nextapps-de/flexsearch) - It is a Next-Generation full text search library for Browser and Node.js.
* [Elasticlunr](https://github.com/weixsong/elasticlunr.js) - This library is based on lunr.js, but more flexible and customized.

## Misc

* [echo](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes.
* [picturefill](https://github.com/scottjehl/picturefill) - A responsive image polyfill for &lt;picture&gt;, srcset, sizes.
* [platform.js](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms.
* [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms.
* [Logical Or Not](https://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* [BitSet.js](https://github.com/infusion/BitSet.js) - A JavaScript Bit-Vector implementation.
* [spoiler-alert](https://github.com/joshbuddy/spoiler-alert) - SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site.
* [jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) - Vibration API Wrappers
* [list.js](https://github.com/javve/list.js) - Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
https://listjs.com
* [mixitup](https://github.com/patrickkunka/mixitup) - MixItUp - A Filter & Sort Plugin.
* [grid](https://github.com/hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists.
* [jquery-match-height](https://github.com/liabru/jquery-match-height) - a responsive equal heights plugin for jQuery.
* [SurveyJS](https://github.com/surveyjs/survey-library) - SurveyJS is a JavaScript Survey and Form Library. https://surveyjs.io/
* [Array Explorer](https://github.com/sdras/array-explorer) and [Object Explorer](https://objectexplorer.netlify.app/) - Resources to help figure out what native JavaScript method would be best to use at any given time.
* [Clipboard.js](https://clipboardjs.com/) - "Copy to clipboard" without Flash or use of Frameworks.
* [ky](https://github.com/sindresorhus/ky) - Tiny and elegant HTTP client based on the browser Fetch API.
* [Fcal](https://github.com/5anthosh/fcal) -  Math expression evaluator.
* [emoji-button](https://github.com/joeattardi/emoji-button) - Vanilla JavaScript emoji picker component.
* [iooxa](https://github.com/iooxa/article) - Components for interactive scientific writing, reactive documents and explorable explanations.
* [Idyll](https://github.com/idyll-lang/idyll) - Create explorable explanations and interactive storytelling essays. Can be [embedded in HTML](https://github.com/idyll-lang/idyll-embed).
* [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) - Algorithms and data structures implemented in JavaScript with explanations and links to further readings.
* [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) - Makes a visitor identifier from a browser fingerprint that stays the same in incognito mode and when browser data is purged.
* [Peg.js](https://github.com/pegjs/pegjs) - A simple parser generator for JavaScript that produces fast parsers with excellent error reporting. Usable from your browser, from the command line, or via JavaScript API.
* [lune](https://github.com/ryanseys/lune) - Library to calculate the phases of the moon accurately.
* [jsemu](https://github.com/fcambus/jsemu) - A list of emulators written in the JavaScript programming language.
* [dir2tree](https://github.com/zakarialaoui10/dir2tree) - A user-friendly Node.js tool for creating organized json tree from a root directory .



# Worth Reading
 
* [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) - Possibly the best book written on modern JavaScript, completely readable online for free, or can be bought to support the author.
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) - An easy-to-read, quick reference for JS best practices, accepted coding standards, and links around the Web.
* [JSbooks](https://github.com/revolunet/JSbooks) - Directory of free JavaScript ebooks.
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* [SJSJ](https://github.com/KittyGiraudel/SJSJ) - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
* [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) - A comprehensive guide through a set of steps to publish a JavaScript open source library.
* [JavaScript Tutorials](https://hackr.io/tutorials/learn-javascript) - Learn Javascript online from a diverse range of user ranked online tutorials.
* [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) - Pragmatic, balanced FP in JavaScript.
* [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) - Clean Code concepts adapted for JavaScript.


# Other Awesome Lists
 
* [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css)
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome)
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
* [jnv/list](https://github.com/jnv/lists)
* [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs)
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo)
* [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools)
* [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning)
* [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents)
* [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg)
* [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo)
* [instanceofpro/awesome-backbone](https://github.com/sadcitizen/awesome-backbone)
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react)
* [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch)
* [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery)
* [davidyezsetz/you-might-not-need-jquery-plugins](https://github.com/davidyezsetz/you-might-not-need-jquery-plugins)
* [MaximAbramchuck/awesome-interviews](https://github.com/MaximAbramchuck/awesome-interview-questions)
* [denolib/awesome-deno](https://github.com/denolib/awesome-deno)
* [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun)

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.
