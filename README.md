# my_npm_package
[![npm (scoped)](https://img.shields.io/npm/v/@djane/my_npm_package.svg)](https://www.npmjs.com/package/@djane/my_npm_package)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@djane/my_npm_package.svg)](https://www.npmjs.com/package/@djane/my_npm_package)

Removes all spaces from a string.

## Install

```
$ npm isntall @djane/my_npm_package
```

## Usage
```js
const tiny = require("@djane/my_npm_package");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at my_npm_package (<anonymous>:2:41)
//    at <anonymous>:1:1
```
