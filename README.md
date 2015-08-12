# babelify-es6-polyfill
A pure ES5 and ES6 polyfill for use with [babelify](https://github.com/babel/babelify) that only includes standardised features

This project is a fork from [babel-es6-polyfill](https://github.com/JasonBerry/babel-es6-polyfill) which is currently depended on older version of core-js and without including ES5 polyfill.

## Why?
You may prefer to use this polyfill if:

* you'd rather use only language features that are on the standards track (e.g. no window.setImmediate)
* you'd rather *not* use language features that are still in proposal state, and are quite likely to change

## Installation
```
$ npm install babelify-es6-polyfill --save
```

## How to use the Polyfill
This polyfill is intended for use with babelify only. To include the polyfill you need to require it at the top of the entry point to your application.

```
require('babelify-es6-polyfill');
```
