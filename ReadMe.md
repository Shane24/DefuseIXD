Website for IXDA Dublin - Defuse 2016

## Getting Started

If you don't have Gulp or Bower already installed: 

- Install dependencies: `npm install --global yo gulp-cli bower` (may need to run as sudo for global installs)

If you already have Gulp & Bower installed:

- Run `gulp serve` to preview build, spin up a local web server, and watch for changes
- Run `bower install --save <package>` to install frontend dependencies
- Run `gulp serve:test` to run the tests in the browser
- Run `gulp` to build your webapp for production indo 'dist' folder
- Run `gulp serve:dist` to preview the production build

## Features

Please see [gulpfile](app/templates/gulpfile.js)

* Using [Babel](https://babeljs.io)
* CSS Autoprefixing
* Built-in preview server with BrowserSync
* Compile Sass with [libsass](http://libsass.org)
* Lint your scripts
* Map compiled CSS to source stylesheets with source maps
* Image optimization
* Automagically wire-up dependencies installed with [Bower](http://bower.io)

## libsass

Keep in mind that libsass is feature-wise not fully compatible with Ruby Sass. Check out [this](http://sass-compatibility.github.io) curated list of incompatibilities to find out which features are missing.