# babel-preset-updated

> Babel preset

## Install

```sh
$ npm install --save-dev babel-preset-updated
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["focus"]
}
```

### Via CLI

```sh
$ babel script.js --presets focus
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["focus"]
});
```
