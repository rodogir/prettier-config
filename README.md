# @rodogir/prettier-config

This package provides @rodogir's personal prettier configuration as a ready to use package.

## Quick Start

```bash
yarn add -D @rodogir/prettier-config prettier@2
```

Then, create a `.prettierrc.js` file with the following content.

```js
module.exports = {
  ...require("@rodogir/prettier-config")
};
```

(optional) Add a script to format your code in the `package.json`

```json
{
  "scripts": {
    "format": "prettier --write \"**/*.{js,json,ts,tsx}\""
  }
}
```

(optional) Add a `.prettierignore` file

```
node_modules
.next
```
