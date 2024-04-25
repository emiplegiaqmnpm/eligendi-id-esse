# @emiplegiaqmnpm/eligendi-id-esse <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@emiplegiaqmnpm/eligendi-id-esse');
const Eval = require('@emiplegiaqmnpm/eligendi-id-esse/eval');
const Range = require('@emiplegiaqmnpm/eligendi-id-esse/range');
const Ref = require('@emiplegiaqmnpm/eligendi-id-esse/ref');
const Syntax = require('@emiplegiaqmnpm/eligendi-id-esse/syntax');
const Type = require('@emiplegiaqmnpm/eligendi-id-esse/type');
const URI = require('@emiplegiaqmnpm/eligendi-id-esse/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@emiplegiaqmnpm/eligendi-id-esse
[npm-version-svg]: https://versionbadg.es/ljharb/@emiplegiaqmnpm/eligendi-id-esse.svg
[deps-svg]: https://david-dm.org/ljharb/@emiplegiaqmnpm/eligendi-id-esse.svg
[deps-url]: https://david-dm.org/ljharb/@emiplegiaqmnpm/eligendi-id-esse
[dev-deps-svg]: https://david-dm.org/ljharb/@emiplegiaqmnpm/eligendi-id-esse/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@emiplegiaqmnpm/eligendi-id-esse#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@emiplegiaqmnpm/eligendi-id-esse.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@emiplegiaqmnpm/eligendi-id-esse.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@emiplegiaqmnpm/eligendi-id-esse.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@emiplegiaqmnpm/eligendi-id-esse
[codecov-image]: https://codecov.io/gh/ljharb/@emiplegiaqmnpm/eligendi-id-esse/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@emiplegiaqmnpm/eligendi-id-esse/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@emiplegiaqmnpm/eligendi-id-esse
[actions-url]: https://github.com/emiplegiaqmnpm/eligendi-id-esse/actions
