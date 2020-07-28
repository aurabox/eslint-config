## Install

```sh
npm i @aurabox/eslint-config-react
```


## Use

This config is meant to be applied on top of one of the other base configs.

```js
module.exports = {
  'root': true,
  'extends': [
    '@aurabox/eslint-config-ts',
    '@aurabox/eslint-config-react'
  ]
};
```
