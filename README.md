![npm (scoped)](https://img.shields.io/npm/v/@r.yadav9969/tiny2)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@r.yadav9969/tiny2)](https://www.npmjs.com/package/@r.yadav9969/tiny2)


Removes all spaces from a string.

## Install

```
$ npm install @r.yadav9969/tiny2
```

## Usage

```js
const tiny = require("@r.yadav9969/tiny2");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
