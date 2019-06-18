# sophonjs-config
Common configuration for SophonJS libraries

## Usage

For guidance on how to to use configuration within an ``SophonJS`` repo see the different
config files (e.g. ``tsconfig.json``) on the [SRLP](https://octonion.institute/susy-js/srlp) library
for reference.

## Development

This is a [lerna](https://github.com/lerna/lerna) monorepo. You need to have lerna installed 
globally in your system.

Bootstrapping:

```sh
lerna bootstrap
```

Publication with 2FA enabled:

```sh
NPM_CONFIG_OTP=123456 lerna publish
```
