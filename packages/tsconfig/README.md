# Ingrid AB tsconfig

This is TypeScript configuration used in Ingrid AB projects. To use it you need to
install it first:

```shell
npm install @ingridab/styleguide
```

Then create `tsconfig.json` file inside your project with following contents:

```json
{
  "extends": "@ingridab/tsconfig"
}
```

And your are ready to go 🚀.

If you need to override some settings:

```json
{
  "extends": "@ingridab/tsconfig",
  "paths": {
    "~src/*": ["src/*"]
  }
}
```
