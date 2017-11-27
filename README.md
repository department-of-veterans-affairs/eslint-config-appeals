# eslint-config-appeals
ESLint config for Appeals JS.

## Usage
You must manually install all plugins that this config uses. Look for all entries beginning with `plugin:` in the `extends` field in `.eslintrc.js`, and add them to your `package.json`. For instance:

```js
  extends: [
    'plugin:react/recommended',
    'plugin:import/errors',
    'plugin:import/warnings'
  ],
```

This is required because of a [limitation in ESLint configs](https://github.com/eslint/eslint/issues/3458).
