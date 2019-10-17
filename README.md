# i40 JavaScript Style [![npm][npm-image]][npm-url]

[npm-image]: https://img.shields.io/npm/v/@i40/eslint-config.svg
[npm-url]: https://www.npmjs.com/package/@i40/eslint-config

An ESLint Shareable Config for i40 flavored JavaScript Standard Style

## Install

`npx install-peerdeps --dev @i40/eslint-config`

## Usage

Add to either package.json or .eslintrc:

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

##### .eslintrc

```
{
  "extends": "@i40/eslint-config"
}
```

## Rules

1. Comma dangle (comma-dangle)
   always-multiline: Requires trailing commas for multiline object and array literals
2. Space before function parenthesis: (space-before-function-paren)
   never: Disallows any space followed by the `(` of arguments
