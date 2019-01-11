# @mrseanbaines/tiny

![](https://img.shields.io/npm/v/@mrseanbaines/tiny.svg?style=for-the-badge)
![](https://img.shields.io/bundlephobia/min/@mrseanbaines/tiny.svg?style=for-the-badge)

Removes all spaces from a string.

## Install

```
$ npm install @mrseanbaines/tiny
```

## Usage

```js
const tiny = require("@mrseanbaines/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
