# @abhiyadav1323/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@abhiyadav1323/tiny.svg)](https://www.npmjs.com/package/@abhiyadav1323/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@abhiyadav1323/tiny.svg)](https://www.npmjs.com/package/@abhiyadav1323/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @abhiyadav1323/tiny
```

## Usage

```js
const tiny = require("@abhiyadav1323/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
