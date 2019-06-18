# @sophonjs/config-tsc

Common `TypeScript` configuration for `SophonJS` libraries.

Tool: [TypeScript](https://www.typescriptlang.org/)

Supported Version: `^3.2.2`

Exposed CLI commands:

- `sophonjs-config-tsc`
- `sophonjs-config-build`

## Usage

Add `tsconfig.json`:

```json
{
  "extends": "@sophonjs/config-tsc",
  "include": ["src/**/*.ts", "test/**/*.ts"]
}
```

Add `tsconfig.prod.json`:

```json
{
  "extends": "@sophonjs/config-tsc",
  "compilerOptions": {
    "outDir": "./dist"
  },
  "include": ["src/**/*.ts"]
}
```

Use CLI commands above in `package.json`:

```json
  "scripts": {
    "tsc": "sophonjs-config-tsc",
    "build": "sophonjs-config-build"
  }
```



