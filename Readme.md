
# curry

[![Build status][travis-image]][travis-url]
[![Git tag][git-image]][git-url]
[![NPM version][npm-image]][npm-url]
[![Code style][standard-image]][standard-url]

Simple curry function.

## Installation

    $ npm install @micro-js/curry

## Usage

```js
var curry = require('@micro-js/curry')

var add = curry(function (a, b) {
  return a + b
})

var addOne = add(1)
addOne(1) // => 1

```

## API

### curry(fn)

- `fn` - function to curry

**Returns:** curried partial of `fn`

## License

MIT

[travis-image]: https://img.shields.io/travis/micro-js/curry.svg?style=flat-square
[travis-url]: https://travis-ci.org/micro-js/curry
[git-image]: https://img.shields.io/github/tag/micro-js/curry.svg
[git-url]: https://github.com/micro-js/curry
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard
[npm-image]: https://img.shields.io/npm/v/@micro-js/curry.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@micro-js/curry
