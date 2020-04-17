# @webb/config-stylelint

> Opinionated Stylelint configuration



## Install

```sh
# Install this module, with Stylelint and the Stylelint Order module
$ npm i @webb/config-stylelint stylelint stylelint-order -D
```



## Usage

Add these lines to your `.stylelintrc` file:

```js
{
  extends: "@webb/config-stylelint",
  plugins: [
    "stylelint-order"
  ]
}
```

In your `scripts` block in your `package.json` file:

```json
// In this example, you may have a number of test scripts so your Sass
// one is namespaced. To call it, you just run "npm run test:sass" and
// your Sass files are linted! You can name your script w/e you want.
"test:sass": "stylelint '**/*.scss'"
```
