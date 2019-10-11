# i40 JavaScript Style [![npm][npm-image]][npm-url]

[npm-image]: https://img.shields.io/npm/v/@i40/eslint-config.svg
[npm-url]: https://www.npmjs.com/package/@i40/eslint-config

An ESLint Shareable Config for i40 flavored JavaScript Standard Style

## Install

`npm i -D @i40/eslint-config eslint@^6.5.1 eslint-plugin-import@^2.18.2 eslint-plugin-node@^10.0.0 eslint-plugin-promise@^4.2.1 eslint-plugin-standard@^4.0.1 eslint-config-standard@^14.1.0`

## Usage

Add to either package.json or .eslintrc.json:

##### package.json

```
{
  // …
  "eslintConfig": {
    "extends": "@i40/eslint-config"
  }
  // …
}
```

##### .eslintrc.json

```
{
  "extends": "@i40/eslint-config"
}
```

## Rules

1. Comma dangle (comma-dangle)
   always-multiline: Requires trailing commas for multiline object and array literals
