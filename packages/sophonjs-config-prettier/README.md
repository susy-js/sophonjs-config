# @sophonjs/config-prettier

Common formatting configuration for `SophonJS` libraries.

Tool: [Prettier](https://prettier.io/)

Supported Version: `^1.15.3`

Exposed CLI commands:

- `sophonjs-config-format`
- `sophonjs-config-format-fix`

## Usage

Add `prettier.config.js`:

```javascript
module.exports = require('@sophonjs/config-prettier')
```

Add `.prettierignore`:

```shell
node_modules
.vscode
package.json
dist
.nyc_output
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "format": "sophonjs-config-format",
    "format-fix": "sophonjs-config-format-fix"
  }
```



