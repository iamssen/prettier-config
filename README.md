# Prettier config

## Basic Usage

Install dependencies.

```sh
npm install prettier @lunit/prettier-config --save-dev
```

Add this config into package.json.

```json
{
  "prettier": "@lunit/prettier-config"
}
```

Or if you want to customize this config. make a '.prettierrc.js' file on the project root. 

```js
module.exports = {
  ...require("@lunit/prettier-config"),
  // your custom config
  semi: false
};
```
