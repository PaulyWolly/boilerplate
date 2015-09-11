# [Z63 Boilerplate](http://zerosixthree.se)

[![Build Status](https://api.travis-ci.org/sebastianekstrom/boilerplate.svg)](https://travis-ci.org/sebastianekstrom/boilerplate)
[![devDependency Status](https://david-dm.org/sebastianekstrom/boilerplate/dev-status.svg)](https://david-dm.org/sebastianekstrom/boilerplate#info=devDependencies)

Boilerplate for your projects made with [Gulp](http://gulpjs.com//), [Sass](http://sass-lang.com/), [Jeet.gs](http://jeet.gs/) and [Browserify](http://browserify.org/).

## Features

* No styling at all, this is a completely bare boilerplate containing only the essential things you need
* A solid Sass and Javascript foundation
* Includes [Browserify](http://browserify.org/) to handle Javascript dependencies
* Includes [Normalize.css](http://necolas.github.com/normalize.css/) to make browser rendering more consistent
* Includes [jQuery](https://jquery.com/) and [Modernizr](http://modernizr.com/)
* CSS helper classes
* A performance optimized print CSS from [HTML5BP](https://github.com/h5bp/html5-boilerplate)
* Commonly used CSS components such as the [Media Object](http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/) and the [Flag Object](http://goo.gl/YR3ffA)
* A Gulpfile with all your basic needs (Sass/Browserify, local server, minification, linting)
* Grid system from [Jeet.gs](http://jeet.gs/)
* Component based file and folder structure, to help create re-usable and maintainable CSS
* A Sass library of commonly used mixins and placeholder selectors

## Download

- [Download the latest release](https://github.com/sebastianekstrom/boilerplate/archive/v1.7.zip)
- Clone the repo: `git clone https://github.com/sebastianekstrom/boilerplate.git`
- Install with [Bower](http://bower.io): `bower install Z63-Boilerplate`

## Getting started

Step 1. Install [NodeJS](http://nodejs.org/download/)

Step 2. Install [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
```shell
npm install --global gulp
```

Step 3. Install the npm dependencies
```shell
cd path/to/project
npm install
```

Step 4. Run Gulp's default task
```shell
gulp
```

## Gulp tasks

There are two Gulp tasks; `gulp` and `gulp dist`.

`gulp` is the default task and will concatenate all Javascript files in to `dist/js/script__1.7.0.js` as well as running JSHint on them. The task will also concatenate all Sass files into `dist/css/style__1.7.0.css` and also run autoprefixer on the outputted CSS file to ensure all the correct vendor prefixes are included. `gulp` also uses the `gulp watch` task, so it automatically runs every time a JS/SCSS file changes.

`gulp dist` is the production task and will do everything the default task does, as well as compressing the JS and CSS files.

## License

The code is available under the [MIT license](LICENSE.txt).
