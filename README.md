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
  "presets": ["updated"]
}
```

### Via CLI

```sh
$ babel script.js --presets updated
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["updated"]
});
```
