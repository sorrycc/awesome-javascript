# Awesome JavaScript

A collection of awesome browser-side  JavaScript libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Loaders](#loaders)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Non-MVC Frameworks](#non-mvc-frameworks)
  * [Templating Engines](#templating-engines)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
  * [Editors](#editors)
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
    * [Class](#class)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#media)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Vision Detection](#vision-detection)
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
  * Mobile
    * [Gesture](#gesture)
  * [Maps](#maps)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [Misc](#misc)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----


## Package Managers

*Host the javascript libraries and provide tools for fetching and packaging them.*

* [Bower](https://github.com/bower/bower) - A package manager for the web.
* [component](https://github.com/component/component) - Client package management for building better web applications.
* [spm](https://github.com/spmjs/spm) - Brand new static package manager.
* [jam](https://github.com/caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository.
* [jspm](https://github.com/jspm/jspm-cli) - Frictionless browser package management.
* [Ender](https://github.com/ender-js/Ender) - The no-library library.
* [volo](https://github.com/volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects.
* [Duo](https://github.com/duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.


## Loaders
*Module or loading system for JavaScript.*

* [RequireJS](https://github.com/jrburke/requirejs) - A file and module loader for JavaScript.
* [browserify](https://github.com/substack/node-browserify) - Browser-side require() the node.js way.
* [SeaJS](https://github.com/seajs/seajs) - A Module Loader for the Web.
* [HeadJS](https://github.com/headjs/headjs) - The only script in your HEAD.
* [curl](https://github.com/cujojs/curl) - A small, fast, extensible module loader that handles AMD, CommonJS Modules/1.1, CSS, HTML/text, and legacy scripts.
* [lazyload](https://github.com/rgrove/lazyload/) - Tiny, dependency-free async JavaScript and CSS loader.
* [script.js](https://github.com/ded/script.js) - Asyncronous JavaScript loader and dependency manager.
* [systemjs](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader.
* [yepnope.js](https://github.com/SlexAxton/yepnope.js) - An Asynchronous Conditional Resource Loader.
* [webpack](https://github.com/webpack/webpack) - Module loader made for big projects. Supports AMD, CommonJS, and more.


## Testing Frameworks

### Frameworks

* [mocha](https://github.com/visionmedia/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
* [jasmine](https://github.com/pivotal/jasmine) - DOM-less simple JavaScript testing framework.
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* [jest](http://github.com/facebook/jest) - Painless Javascript Unit Testing.
* [prova](http://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify

### Assertion

* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework. [![](http://spmjs.io/badge/chai)](http://spmjs.io/package/chai)
* [Sinon.JS](https://github.com/cjohansen/Sinon.JS) - Test spies, stubs and mocks for JavaScript. [![](http://spmjs.io/badge/sinon)](http://spmjs.io/package/sinon)
* [expect.js](https://github.com/LearnBoost/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser. [![](http://spmjs.io/badge/expect.js)](http://spmjs.io/package/expect.js)

### Coverage

* [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool.
* [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner

* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* [casperjs](https://github.com/n1k0/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [totoro](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool.
* [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript.
* [nightwatch](https://github.com/beatfactor/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.


## QA Tools

* [JSHint](https://github.com/jshint/jshint/) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
* [jsfmt](https://github.com/rdio/jsfmt) - For formatting, searching, and rewriting JavaScript.
* [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
* [buddy.js](https://github.com/danielstjules/buddy.js) - Magic number detection for JavaScript.
* [ESLint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript.


## MVC Frameworks and Libraries

* [angular.js](https://github.com/angular/angular.js) - HTML enhanced for web apps.
* [backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events. [![](http://spmjs.io/badge/backbone)](http://spmjs.io/package/backbone)
* [batman.js](http://batmanjs.org/) - The best JavaScript framework for Rails developers.
* [ember.js](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications.
* [meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework.
* [ractive](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation. [![](http://spmjs.io/badge/ractive)](http://spmjs.io/package/ractive)
* [vue](https://github.com/yyx990803/vue) - Intuitive, fast & composable MVVM for building interactive interfaces. [![](http://spmjs.io/badge/vue)](http://spmjs.io/package/vue)
* [knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* [spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications.
* [espresso.js](https://github.com/techlayer/espresso.js) - A minimal javascript library for crafting user interfaces. [![](http://spmjs.io/badge/espresso.js)](http://spmjs.io/package/espresso.js)
* [canjs](https://github.com/bitovi/canjs) - Can do JS, better, faster, easier.
* [react](https://facebook.github.io/react/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [thorax](https://github.com/walmartlabs/thorax) - Strengthening your Backbone.
* [chaplin](https://github.com/chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library.
* [marionette](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* [ripple](https://github.com/ripplejs/ripple) - A tiny foundation for building reactive views.
* [rivets](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution.
* [derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * [derby-awesome](https://github.com/onerussell/awesome-derby) - A collection of awesome derby components
* [way.js](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding. [![](http://spmjs.io/badge/way.js)](http://spmjs.io/package/way.js)
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).

## Non-MVC Frameworks

* [famous](https://github.com/Famous/famous) - A JavaScript framework for everyone who wants to build beautiful experiences on any device.


## Templating Engines
*Templating engines allow you to perform string interpolation.*

* [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript. [![](http://spmjs.io/badge/mustache)](http://spmjs.io/package/mustache)
* [handlebars.js](https://github.com/wycats/handlebars.js/) - An extension to the Mustache templating language. [![](http://spmjs.io/badge/handlebars)](http://spmjs.io/package/handlebars)
* [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language. [![](http://spmjs.io/badge/hogan.js)](http://spmjs.io/package/hogan.js)
* [doT](https://github.com/olado/doT) - The fastest + concise javascript template engine for nodejs and browsers.
* [dustjs](https://github.com/linkedin/dustjs/) - Asynchronous templates for the browser and node.js.
* [eco](https://github.com/sstephenson/eco/) - Embedded CoffeeScript templates.
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies.
* [t.js](https://github.com/jasonmoo/t.js) - A tiny javascript templating framework in ~400 bytes gzipped.


## Data Visualization
*Data visualization tools for the web.*

* [d3](https://github.com/mbostock/d3) - A JavaScript visualization library for HTML and SVG.  [![](http://spmjs.io/badge/d3)](http://spmjs.io/package/d3)
  * [metrics-graphics](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts.
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library.
* [Chart.js](https://github.com/nnnick/Chart.js) - Simple HTML5 Charts using the <canvas> tag. [![](http://spmjs.io/badge/chart.js)](http://spmjs.io/package/chart.js)
* [paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* [fabric.js](https://github.com/kangax/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* [peity](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts.
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library.
* [echarts](https://github.com/ecomfe/echarts) - Enterprise Charts.
* [vis](https://github.com/almende/vis) - Dynamic, browser-based visualization library.
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
* [nvd3](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG.
* [heatmap.js](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps.
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - A plugin for the jQuery javascript library to generate small sparkline charts directly in the browser.
* [xCharts](https://github.com/tenxer/xCharts) - A D3-based library for building custom charts and graphs.
* [trianglify](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js
* [d3-cloud](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript.
* [d4](https://github.com/heavysixer/d4) - A friendly reusable charts DSL for D3.
* [dimple.js](http://dimplejs.org) -  Easy charts for business analytics powered by d3
* [chartist-js](https://github.com/gionkunz/chartist-js) - Simple responsive charts.
* [epoch](https://github.com/fastly/epoch) - A general purpose real-time charting library.
* [c3](https://github.com/masayuki0812/c3) - D3-based reusable chart library.

There're also some great commercial libraries, like [amchart](http://www.amcharts.com/) and [highchart](http://www.highcharts.com/).


## Timeline

* [TimelineJS](https://github.com/NUKnightLab/TimelineJS) - A Storytelling Timeline built in JavaScript.
* [timesheet.js](https://github.com/semu/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets.


## Editors

* [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor).
* [CodeMirror](https://github.com/marijnh/CodeMirror) - In-browser code editor.  [![](http://spmjs.io/badge/codemirror)](http://spmjs.io/package/codemirror)
* [esprima](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis.
* [quill](https://github.com/quilljs/quill) - A cross browser rich text editor with an API.
* [medium-editor](https://github.com/daviferreira/medium-editor) - Medium.com WYSIWYG editor clone.
* [pen](https://github.com/sofish/pen) - enjoy live editing (+markdown).
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium.
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor.
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - The best web text editor for everyone.
* [editor](https://github.com/lepture/editor) - A markdown editor. still on development.
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* [jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON.
* [vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent ~/.vimrc


## Files
*Libraries for working with files.*

* [Papa Parse](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* [jBinary](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* [underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt.  [![](http://spmjs.io/badge/underscore)](http://spmjs.io/package/underscore)
* [lodash](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras.  [![](http://spmjs.io/badge/lodash)](http://spmjs.io/package/lodash)
* [Sugar](https://github.com/andrewplummer/Sugar) - A Javascript library for working with native objects.
* [lazy.js](https://github.com/dtao/lazy.js) - Like Underscore, but lazier. [![](http://spmjs.io/badge/lazy.js)](http://spmjs.io/package/lazy.js)
* [ramda](https://github.com/CrossEye/ramda) - A practical functional library for Javascript programmers.
* [mout](https://github.com/mout/mout) - Modular JavaScript Utilities.


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJs](https://github.com/Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript.
* [Bacon](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript.
* [Kefir](https://github.com/pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption.


## Data Structure
*Data structure libraries to build a more sophisticated application.*

* [immutable-js](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector. [![](http://spmjs.io/badge/immutable)](http://spmjs.io/package/immutable)
* [mori](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [buckets](https://github.com/mauriciosantos/buckets) - A complete, fully tested and documented data structure library written in JavaScript.
* [hashmap](https://github.com/flesler/hashmap) - Simple hashmap implementation that supports any kind of keys.


## Date
*Date Libraries.*

* [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.  [![](http://spmjs.io/badge/moment)](http://spmjs.io/package/moment)
* [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js.
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago"). [![](http://spmjs.io/badge/timeago)](http://spmjs.io/package/timeago)
* [timezone-js](https://github.com/mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data.
* [date](https://github.com/MatthewMueller/date) - Date() for humans. [![](http://spmjs.io/badge/date)](http://spmjs.io/package/date)
* [ms.js](https://github.com/guille/ms.js) - Tiny milisecond conversion utility. [![](http://spmjs.io/badge/ms)](http://spmjs.io/package/ms)


## String
*String Libraries.*

* [underscore.string](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js javascript library. [![](http://spmjs.io/badge/underscore.string)](http://spmjs.io/package/underscore.string)
* [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods. [![](http://spmjs.io/badge/string.js)](http://spmjs.io/package/string.js)
* [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript. [![](http://spmjs.io/badge/he)](http://spmjs.io/package/he)
* [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript. [![](http://spmjs.io/badge/multiline)](http://spmjs.io/package/multiline)
* [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings. [![](http://spmjs.io/badge/query-string)](http://spmjs.io/package/query-string)
* [URI.js](https://github.com/medialize/URI.js/) - Javascript URL mutation library. [![](http://spmjs.io/badge/urijs)](http://spmjs.io/package/urijs)
* [jsurl](https://github.com/Mikhus/jsurl) - Lightweight URL manipulation with JavaScript.
* [sprintf.js](https://github.com/alexei/sprintf.js) - A sprintf implementation.


## Number

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers. [![](http://spmjs.io/badge/numeral)](http://spmjs.io/package/numeral)
* [odometer](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease. [![](http://spmjs.io/badge/odometer)](http://spmjs.io/package/odometer)
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) javascript currency conversion library, for web & nodeJS.


## Storage

* [store.js](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood. [![](http://spmjs.io/badge/store)](http://spmjs.io/package/store)
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API. [![](http://spmjs.io/badge/localforage)](http://spmjs.io/package/localforage)
* [jStorage](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side.
* [cross-storage](https://github.com/zendesk/cross-storage) - Cross domain local storage, with permissions.
* [basket.js](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage.
* [basil.js](https://github.com/Wisembly/basil.js) - The missing Javascript smart persistent layer. [![](http://spmjs.io/badge/basil.js)](http://spmjs.io/package/basil.js)
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* [Cookies](https://github.com/ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library.


## Color

* [randomColor](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript. [![](http://spmjs.io/badge/randomcolor)](http://spmjs.io/package/randomcolor)
* [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations. [![](http://spmjs.io/badge/chroma-js)](http://spmjs.io/package/chroma-js)
* [color](https://github.com/harthur/color) - JavaScript color conversion and manipulation library. [![](http://spmjs.io/badge/color)](http://spmjs.io/package/color)
* [colors](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web.
* [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.
* [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript. [![](http://spmjs.io/badge/tinycolor)](http://spmjs.io/package/tinycolor)

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next](https://github.com/jamuhl/i18next) - internationalisation (i18n) with javascript the easy way.
* [polyglot](https://github.com/airbnb/polyglot.js) - tiny i18n helper library.

## Class

* [klass](https://github.com/ded/klass) - A utility for creating expressive classes in JavaScript. [![](http://spmjs.io/badge/klass)](http://spmjs.io/package/klass)
* [augment](https://github.com/javascript/augment) - The world's smallest and fastest classical JavaScript inheritance pattern. [![](http://spmjs.io/badge/augment)](http://spmjs.io/package/augment)


## Control Flow

* [async](https://github.com/caolan/async) - Async utilities for node and the browser.
* [q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript. [![](http://spmjs.io/badge/q)](http://spmjs.io/package/q)
* [step](https://github.com/creationix/step/) - An async control-flow library that makes stepping through logic easy. [![](http://spmjs.io/badge/step)](http://spmjs.io/package/step)
* [contra](https://github.com/bevacqua/contra/) - Asynchronous flow control with a functional taste to it.
* [Bluebird](https://github.com/petkaantonov/bluebird/) - fully featured promise library with focus on innovative features and performance.
* [when](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies.


## Routing

* [director](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript.  [![](http://spmjs.io/badge/director)](http://spmjs.io/package/director)
* [page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes).  [![](http://spmjs.io/badge/page)](http://spmjs.io/package/page)
* [pathjs](https://github.com/mtrpcic/pathjs) - Simple, lightweight routing for web browsers.
* [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes.
* [davis.js](https://github.com/olivernn/davis.js) - RESTful degradable JavaScript routing using pushState.


## Security

* [DOMPurify](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.


## Log

* [log](https://github.com/adamschwartz/log) - Console.log with style. [![](http://spmjs.io/badge/log)](http://spmjs.io/package/log)
* [Conzole](https://github.com/Oaxoa/Conzole) - A debug panel built in javascript that wraps javascript native console object methods and functionality in a panel displayed inside the page.
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity.
* [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.


## RegExp


## Media

* [Ion.Sound](https://github.com/IonDen/ion.sound) - Simple sounds on any web page [![](http://spmjs.io/badge/ion-sound)](http://spmjs.io/package/ion-sound)


## Voice Command

* [annyang](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition.
* [voix.js](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games.


## API

* [bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser.

## Vision Detection

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten.

## Code highlighting

* [Highlight.js](https://github.com/isagalaev/highlight.js) - Javascript syntax highlighter.
* [PrismJS](https://github.com/LeaVerou/prism) - Lightweight, robust, elegant syntax highlighting.


## Loading Status
*Libraries for indicate load status.*

* [NProgress](http://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications. [![](http://spmjs.io/badge/nprogress)](http://spmjs.io/package/nprogress)
* [Spin.js](https://github.com/fgnass/spin.js) - A spinning activity indicator. [![](http://spmjs.io/badge/spin.js)](http://spmjs.io/package/spin.js)
* [progress.js](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page.
* [pace](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site. [![](http://spmjs.io/badge/pace)](http://spmjs.io/package/pace)
* [topbar](https://github.com/buunguyen/topbar) - Tiny & beautiful site-wide progress indicator. [![](http://spmjs.io/badge/topbar)](http://spmjs.io/package/topbar)
* [nanobar](https://github.com/jacoborus/nanobar) - Very lighweight progress bars. No jQuery. [![](http://spmjs.io/badge/nanobar)](http://spmjs.io/package/nanobar)
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations.
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS.
* [Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators.
* [css-loaders](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS.

Besides libraries, there're [Collection on Codepen](http://codepen.io/collection/HtAne/), and generators like [Ajaxload](http://www.ajaxload.info/), [Preloaders](http://preloaders.net/) and [CSSLoad](http://cssload.net/).


## Validation

* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript. [![](http://spmjs.io/badge/parsleyjs)](http://spmjs.io/package/parsleyjs)
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin.
* [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization.
* [validate.js](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter.
* [validatr](https://github.com/jaymorrow/validatr/) - Cross Browser HTML5 Form Validation.
* [BootstrapValidator](https://github.com/nghuuphuoc/bootstrapvalidator) - The best jQuery plugin to validate form fields. Designed to use with Bootstrap 3.


## Keyboard Wrappers

* [mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript. [![](http://spmjs.io/badge/mousetrap)](http://spmjs.io/package/mousetrap)
* [keymaster](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts. [![](http://spmjs.io/badge/keymaster)](http://spmjs.io/package/keymaster)
* [Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key. [![](http://spmjs.io/badge/keypress)](http://spmjs.io/package/keypress)
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* [jwerty](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events.


## Tours And Guides

* [intro.js](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project. [![](http://spmjs.io/badge/intro.js)](http://spmjs.io/package/intro.js)
* [shepherd](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app. [![](http://spmjs.io/badge/shepherd)](http://spmjs.io/package/shepherd)
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers.
* [tourist](https://github.com/easelinc/tourist) - Simple, flexible tours for your app.
* [chardin.js](https://github.com/heelhook/chardin.js) - Simple overlay instructions for your apps.
* [pageguide](https://github.com/tracelytics/pageguide) - An interactive guide for web page elements using jQuery and CSS3.
* [hopscotch](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages.
* [joyride](https://github.com/zurb/joyride) - jQuery feature tour plugin.


## Notifications

* [messenger](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app. [![](http://spmjs.io/badge/messenger)](http://spmjs.io/package/messenger)
* [noty](https://github.com/needim/noty) - jQuery notification plugin.
* [pnotify](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* [toastr](https://github.com/CodeSeven/toastr) - Simple javascript toast notifications.
* [humane-js](https://github.com/wavded/humane-js) - A simple, modern, browser notification system.
* [smoke.js](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for javascript.


## Sliders

* [Swiper](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions. [![](http://spmjs.io/badge/swiper)](http://spmjs.io/package/swiper)
* [slick](https://github.com/kenwheeler/slick) - The last carousel you'll ever need. [![](http://spmjs.io/badge/slick)](http://spmjs.io/package/slick)
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin.
* [unslider](https://github.com/idiot/unslider) - The simplest jQuery slider there is.
* [colorbox](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery.
* [fancyBox](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* [sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* [vegas](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* [Sequence](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript.
* [reveal.js](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML.


## Range Sliders

* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support.
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - A javascript slider selector that supports dates.
* [noUiSlider](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat.
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill.


## Form Widgets

### Input

* [typeahead.js](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library. [![](http://spmjs.io/badge/typeahead.js)](http://spmjs.io/package/typeahead.js)
* [tag-it](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* [At.js](https://github.com/ichord/At.js) - Add Github like mentions autocomplete to your application. [![](http://spmjs.io/badge/at.js)](http://spmjs.io/package/at.js)
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute.
* [fancyInput](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects.
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure javascript mask input.

### Calendar

* [pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* [Pikaday](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* [fullcalendar](https://github.com/arshaw/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin).
* [rome](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI. [![](http://spmjs.io/badge/rome)](http://spmjs.io/package/rome)

### Select

* [selectize.js](https://github.com/brianreavis/selectize.js) - Selectize is the hybrid of a textbox and select box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc. [![](http://spmjs.io/badge/selectize)](http://spmjs.io/package/selectize)
* [select2](https://github.com/ivaynberg/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results. [![](http://spmjs.io/badge/select2)](http://spmjs.io/package/select2)
* [chosen](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly.

### File Uploader

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery.
* [dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars. [![](http://spmjs.io/badge/dropzone)](http://spmjs.io/package/dropzone)
* [flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* [fine-uploader](https://github.com/Widen/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* [FileAPI](https://github.com/mailru/FileAPI) - A set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [plupload](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.

### Other

* [form](https://github.com/malsup/form) - jQuery Form Plugin.
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted.
* [Countable](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* [card](https://github.com/jessepollak/card) - Make your credit card form better in one line of code.


## Tips

* [tipsy](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery.
* [opentip](https://github.com/enyo/opentip) - An open source javascript tooltip based on the prototype framework. [![](http://spmjs.io/badge/opentip)](http://spmjs.io/package/opentip)
* [qTip2](https://github.com/qTip2/qTip2) - Pretty powerful tooltips.
* [tooltipster](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin.
* [simptip](https://github.com/arashmanteghi/simptip) - A simple CSS tooltip made with Sass.


## Modals and Popups

* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* [jquery-popbox](https://github.com/gristmill/jquery-popbox) - jQuery PopBox UI Element.
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups.
* [vex](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style.
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* [css-modal](https://github.com/drublic/css-modal) - A modal built out of pure CSS.


## Scroll

* [scrollMonitor](https://github.com/sakabako/scrollMonitor) - A simple and fast API to monitor elements as you scroll.
* [headroom](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it.
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* [iscroll](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller.
* [skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* [parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device.
* [stellar.js](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy.
* [plax](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing.
* [jparallax](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect.

## Menu

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.


## Table/Grid

* [jTable](https://github.com/hikalkan/jtable) - A JQuery plugin to create AJAX based CRUD tables.

## Gesture

* [hammer.js](https://github.com/hammerjs/hammer.js) - A javascript library for multi-touch gestures. [![](http://spmjs.io/badge/hammerjs)](http://spmjs.io/package/hammerjs)
* [touchemulator](https://github.com/hammerjs/touchemulator) - Emulate touch input on your desktop.

## Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps.
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine.
* [gmaps](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps.
* [polymaps](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* [kartograph.js](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps.
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin.
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library.


## Animations

* [velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation.
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery.
* [bounce.js](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time.
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers.


## Image Processing

* [lena.js](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions.


## Misc

* [echo](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes. [![](http://spmjs.io/badge/echo.js)](http://spmjs.io/package/echo.js)
* [platform.js](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms. [![](http://spmjs.io/badge/platform.js)](http://spmjs.io/package/platform.js)
* [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms. [![](http://spmjs.io/badge/json3)](http://spmjs.io/package/json3)


# Other Awesome Lists
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome)
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
* [jnv/list](https://github.com/jnv/lists)
* [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs)
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo)


# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
