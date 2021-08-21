# is-odd [![NPM version](https://img.shields.io/npm/v/is-odd.svg?style=flat)](https://www.npmjs.com/package/isodd) [![NPM monthly downloads](https://img.shields.io/npm/dm/is-odd.svg?style=flat)](https://npmjs.org/package/isodd) [![NPM total downloads](https://img.shields.io/npm/dt/is-odd.svg?style=flat)](https://npmjs.org/package/isodd) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/is-odd.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/isodd)

> Returns true if the given number is odd, and is an integer that does not exceed the JavaScript MAXIMUM_SAFE_INTEGER.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save isodd
```

## Usage

Works with strings or numbers.

```js
const isOdd = require('isodd');

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
