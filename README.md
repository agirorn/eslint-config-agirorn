eslint-config-agirorn
=====================

These are my eslint rules there are many like it but this one is mine.

## Usage

Install module

```shelljs
npm i eslint eslint-config-agirorn eslint-plugin-import@latest --save-dev
```

Add **extends** to **.eslintrc**

```json
{
  "extends": "agirorn"
}
```

## Based on [eslint-config-airbnb-base](https://www.npmjs.com/package/eslint-config-airbnb-base)

Then augmented for my personal taste.
* [no-use-before-define](http://eslint.org/docs/rules/no-use-before-define) (*airbnb issue [#872](https://github.com/airbnb/javascript/issues/872)*) Function hoisting is a javascript standard and assists with top down reading of code from least complex part of code to more complex parts.
