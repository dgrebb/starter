# Generic Project Starter

## Front end stuff

A basic project setup containing a [Sass](http://sass-lang.com/) setup and several JavaScript libraries, including [jQuery 1.11.1](http://jquery.com/), [Modernizr 2.8.2](http://modernizr.com/), [Respond.js 1.4.2](https://github.com/scottjehl/Respond/), [Picturefill.js](https://github.com/scottjehl/picturefill/), [jRespond 0.10](https://github.com/ten1seven/jRespond), and [Selectivizr 1.0.3b](https://github.com/keithclark/selectivizr). Big thanks to the original creators of those included libraries (you're awesome!).

Also big thanks to [Anthony Colangelo](https://github.com/acolangelo), the original author of this :)

## Dev workflow stuff

Also included is a package.json and gulpfile.js. Run `npm install` to grab these great development tools:

*Note: You'll need to install Cairo to work with css-sprite:*

`wget https://raw.githubusercontent.com/LearnBoost/node-canvas/master/install -O - | sh`

* [`gulp`](http://gulpjs.com/) - task runner for [nodejs](http://nodejs.org/)
* [`gulp-connect`](https://www.npmjs.org/package/gulp-connect) - sets up a server and livereload
* [`gulp-rename`](https://www.npmjs.org/package/gulp-rename) - helps rename files
* [`gulp-sass`](https://www.npmjs.org/package/gulp-sass) - my css preprocessor of choice
* [`gulp-autoprefixer`](https://www.npmjs.org/package/gulp-autoprefixer) - prefixes css3 properties for browsers that don't yet support them
* [`gulp-concat`](https://www.npmjs.org/package/gulp-concat) - concatenates files together, making many into one
* [`gulp-strip-debug`](https://www.npmjs.org/package/gulp-strip-debug) - removes console.log, alert(), and debugger statements from javascript
* [`canvas`](https://github.com/Automattic/node-canvas) - dependency for css-sprite
* [`css-sprite`](https://www.npmjs.org/package/css-sprite) - makes a sprite out of images
* [`gulp-cleanhtml`](https://www.npmjs.org/package/gulp-cleanhtml) - removes comments and generally cleans up html
* [`gulp-compressor`](https://www.npmjs.org/package/gulp-compressor/) compresses css, js, and html