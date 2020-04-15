# Golden Layout

[![NPM version](https://img.shields.io/npm/v/golden-layout)](https://www.npmjs.com/package/golden-layout) [![License](https://img.shields.io/github/license/golden-layout/golden-layout)](https://img.shields.io/github/license/golden-layout/golden-layout)

<!-- [![NPM version](https://badge.fury.io/js/golden-layout.svg)](http://badge.fury.io/js/golden-layout) [![Build Status](https://travis-ci.org/deepstreamIO/golden-layout.svg?branch=master)](https://travis-ci.org/deepstreamIO/golden-layout) -->

<!-- ![Screenshot](https://cloud.githubusercontent.com/assets/512416/4584449/e6c154a0-4ffa-11e4-81a8-a7e5f8689dc5.PNG) -->

Please note that this project is currently undergoing a larger maintenance and refactoring, we're targeting a 2.0 release somewhere in H1 2020.

## Features

* Full touch support
* Native popup windows
* Completely themeable
* Comprehensive API
* Powerful persistence
* Works in IE8+, Firefox, Chrome
* Reponsive design


## Installation

- src/js/      -> Prototype-based official source untouched (REQUIRES loading JQuery externally)
- src/js_es6/  -> source converted to ES6 modules, with bugfixes, full touch support (BUNDLES JQuery or Zepto)

When you build either types, the library will be in `dist/js/goldenlayout.js`.

For ES6 GoldenLayout is the default export, while all other components have named exports (details in `js_es6/index.js`)

To make the environment ready, clone, cd to project dir, and run: 

`npm i`

Then to start/build each tree run the following:

###### Prototype-based

start: `npm run start`

build: `npm run build`



###### ES6-based / JQuery

start: `npm run start_es6j`

build: `npm run build_es6j`


###### ES6-based / Zepto

start: `npm run start_es6z`

build: `npm run build_es6z`
