# Prettier config

## Basic Usage

Install dependencies.

```sh
npm install prettier @ssen/prettier-config --save-dev
```

Add this config into package.json.

```json
{
  "prettier": "@ssen/prettier-config"
}
```

Or if you want to customize this config. make a '.prettierrc.js' file on the project root. 

```js
module.exports = {
  ...require("@ssen/prettier-config"),
  // your custom config
  semi: false
};
```
