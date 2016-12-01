# conventional-changelog-lint-config-cz

[![npm][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]

[conventional-changelog-lint][] sharable configuration files.

If `.cz-config.js` that is for [@whizark/cz-cli][] or
[cz-customizable][] exists in your package root directory, its
`{types,scopes,scopeOverrides}` are merged with
`rules.{type-enum,scope-enum}`.

## Installation

Install `conventional-changelog-lint-config-cz` as a local dependency.

```sh
npm install conventional-changelog-lint-config-cz --save
```

## Usage

Extend `@whizark/conventional-changelog-lint` in
`.conventional-changelog-lintrc`.

```json
{
    "extends": [
        "cz"
    ]
}
```

[conventional-changelog-lint]: https://github.com/marionebl/conventional-changelog-lint
[@whizark/cz-cli]: https://github.com/whizark/cz-cli
[cz-customizable]: https://github.com/leonardoanalista/cz-customizable

[npm-image]: https://img.shields.io/npm/v/conventional-changelog-lint-config-cz.svg
[npm-url]: https://www.npmjs.com/conventional-changelog-lint-config-cz

[travis-image]: https://travis-ci.org/whizark/conventional-changelog-lint-config-cz.svg?branch=master
[travis-url]: https://travis-ci.org/whizark/conventional-changelog-lint-config-cz
