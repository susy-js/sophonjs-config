# @sophonjs/config-tslint

Common linting configuration for `SophonJS` libraries.

Tool: [TSLint](https://palantir.github.io/tslint/)

Supported Version: `^5.12.0`

Exposed CLI commands:

- `sophonjs-config-tslint`
- `sophonjs-config-tslint-fix`
- `sophonjs-config-lint`
- `sophonjs-config-lint-fix`

## Usage

Add `tslint.json`:

```json
{
  "extends": "@sophonjs/config-tslint"
}
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "tslint": "sophonjs-config-tslint",
    "tslint-fix": "sophonjs-config-tslint-fix",
    "lint": "sophonjs-config-lint",
    "lint-fix": "sophonjs-config-lint-fix"
  }
```

## Installation

This package requires [`typestrict`](https://github.com/krzkaczor/TypeStrict) to be installed.

