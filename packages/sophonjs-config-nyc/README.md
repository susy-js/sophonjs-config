# @sophonjs/config-nyc

Common test coverage configuration for `SophonJS` libraries.

Tool: [nyc](https://istanbul.js.org/)

Supported Version: `^11.7.0`

Exposed CLI commands:

- `sophonjs-config-coverage`
- `sophonjs-config-coveralls`

## Usage

Add `.nycrc`:

```json
{
  "extends": "@sophonjs/config-nyc"
}
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "coverage": "sophonjs-config-coverage",
    "coveralls": "sophonjs-config-coveralls"
  }
```



