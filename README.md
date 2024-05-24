# @taktikangea/assumenda-dolorum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@taktikangea/assumenda-dolorum');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikangea/assumenda-dolorum
[npm-version-svg]: https://versionbadg.es/inspect-js/@taktikangea/assumenda-dolorum.svg
[deps-svg]: https://david-dm.org/inspect-js/@taktikangea/assumenda-dolorum.svg
[deps-url]: https://david-dm.org/inspect-js/@taktikangea/assumenda-dolorum
[dev-deps-svg]: https://david-dm.org/inspect-js/@taktikangea/assumenda-dolorum/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@taktikangea/assumenda-dolorum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikangea/assumenda-dolorum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikangea/assumenda-dolorum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikangea/assumenda-dolorum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikangea/assumenda-dolorum
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikangea/assumenda-dolorum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikangea/assumenda-dolorum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikangea/assumenda-dolorum
[actions-url]: https://github.com/taktikangea/assumenda-dolorum/actions
