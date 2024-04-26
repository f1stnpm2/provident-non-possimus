# @f1stnpm2/provident-non-possimus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Does this JS environment support the `name` property on functions?

## Example

```js
var functionsHaveNames = require('@f1stnpm2/provident-non-possimus');
var assert = require('assert');

assert.equal(functionsHaveNames(), true); // will be `false` in IE 6-8
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@f1stnpm2/provident-non-possimus
[npm-version-svg]: https://versionbadg.es/inspect-js/@f1stnpm2/provident-non-possimus.svg
[deps-svg]: https://david-dm.org/inspect-js/@f1stnpm2/provident-non-possimus.svg
[deps-url]: https://david-dm.org/inspect-js/@f1stnpm2/provident-non-possimus
[dev-deps-svg]: https://david-dm.org/inspect-js/@f1stnpm2/provident-non-possimus/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@f1stnpm2/provident-non-possimus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@f1stnpm2/provident-non-possimus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@f1stnpm2/provident-non-possimus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@f1stnpm2/provident-non-possimus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@f1stnpm2/provident-non-possimus
[codecov-image]: https://codecov.io/gh/inspect-js/@f1stnpm2/provident-non-possimus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@f1stnpm2/provident-non-possimus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@f1stnpm2/provident-non-possimus
[actions-url]: https://github.com/f1stnpm2/provident-non-possimus/actions
