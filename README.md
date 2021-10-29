# is-odd-num [![NPM version](https://img.shields.io/npm/v/is-odd-num.svg?style=flat)](https://www.npmjs.com/package/isodd) [![NPM monthly downloads](https://img.shields.io/npm/dm/is-odd.svg-num?style=flat)](https://www.npmjs.com/package/is-odd-num) [![NPM total downloads](https://img.shields.io/npm/dt/is-odd-num.svg?style=flat)](https://www.npmjs.com/package/is-odd-num) 

> Returns true if the given number is odd, and is an integer that does not exceed the JavaScript MAXIMUM_SAFE_INTEGER.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save is-odd-num
```

## Usage

Works with strings or numbers.

```js
const isOdd = require('is-odd-num');

console.log(isOdd('1')); //=> true
console.log(isOdd('3')); //=> true

console.log(isOdd(0)); //=> false
console.log(isOdd(2)); //=> false
```

## About

<details>
<summary><strong>Contributing</strong></summary>

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

</details>

<details>
<summary><strong>Running Tests</strong></summary>

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

</details>


### License
Released under the [MIT License](LICENSE).

***
