# @diotoborg/repellat-tenetur-cupiditate <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@diotoborg/repellat-tenetur-cupiditate');
const Eval = require('@diotoborg/repellat-tenetur-cupiditate/eval');
const Range = require('@diotoborg/repellat-tenetur-cupiditate/range');
const Ref = require('@diotoborg/repellat-tenetur-cupiditate/ref');
const Syntax = require('@diotoborg/repellat-tenetur-cupiditate/syntax');
const Type = require('@diotoborg/repellat-tenetur-cupiditate/type');
const URI = require('@diotoborg/repellat-tenetur-cupiditate/uri');

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

[package-url]: https://npmjs.org/package/@diotoborg/repellat-tenetur-cupiditate
[npm-version-svg]: https://versionbadg.es/ljharb/@diotoborg/repellat-tenetur-cupiditate.svg
[deps-svg]: https://david-dm.org/ljharb/@diotoborg/repellat-tenetur-cupiditate.svg
[deps-url]: https://david-dm.org/ljharb/@diotoborg/repellat-tenetur-cupiditate
[dev-deps-svg]: https://david-dm.org/ljharb/@diotoborg/repellat-tenetur-cupiditate/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@diotoborg/repellat-tenetur-cupiditate#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/repellat-tenetur-cupiditate.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/repellat-tenetur-cupiditate.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/repellat-tenetur-cupiditate.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/repellat-tenetur-cupiditate
[codecov-image]: https://codecov.io/gh/ljharb/@diotoborg/repellat-tenetur-cupiditate/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@diotoborg/repellat-tenetur-cupiditate/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@diotoborg/repellat-tenetur-cupiditate
[actions-url]: https://github.com/diotoborg/repellat-tenetur-cupiditate/actions
