# Ingrid AB prettier config

This is [prettier](https://prettier.io) configuration used in Ingrid AB projects. To use it you need to install it first:

```shell
npm install @ingridab/prettier-config
```

Then create `prettier.config.js` file inside root of your project with
following contents:

```js
module.exports = require('@ingridab/prettier-config');
```

And your are ready to go 🚀.

If you need to override some settings:

````js
module.exports = Object.assign(
  require("@ingridab/prettier-config/prettier.config"),
  {
    //add overrides here
    singleQuote: true,
    bracketSpacing: true,
  }
);
````
