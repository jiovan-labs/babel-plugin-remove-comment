# @jiovan-labs/babel-plugin-remove-comment

[![NPM version](https://img.shields.io/npm/v/@jiovan-labs/babel-plugin-remove-comment.svg?style=flat)](https://npmjs.org/package/@jiovan-labs/babel-plugin-remove-comment)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](LICENSE.txt)
[![NPM downloads](http://img.shields.io/npm/dm/@jiovan-labs/babel-plugin-remove-comment.svg?style=flat)](https://npmjs.org/package/@jiovan-labs/babel-plugin-remove-comment)

🏅 Removes script comments during babel compilation 👍

## Features

✅ Support removing comments by option

## Quickstart

You can install this package in your typescript project as follows:

```bash
$ npm install @jiovan-labs/babel-plugin-remove-comment --save-dev
```

Enjoy your coding journey with `babel-plugin-remove-comment` ✌️

## Usage

- Using in javascript/typescript

```js
const plugin = require('@jiovan-labs/babel-plugin-remove-comment');
babel.transform(source_code, {
    plugins: [
        [plugin, { scope: 'all' }]
    ]
});
```

- Using in `babel.config.json` or `.babelrc.json` of [babel](https://babeljs.io)

```json
{
    "plugin": [
        ["@jiovan-labs/babel-plugin-remove-comment", {
            "scope": "all"
        }]
    ]
}
```

- Using in `.fatherrc.ts` of [father](https://github.com/umijs/father)

```typescript
{
    extraBabelPlugins: [
        ['@jiovan-labs/babel-plugin-remove-comment', {
            scope: 'all'
        }]
    ]
}
```

## Option

Here is the available option:

| Param Name | Param Value                    | Value Type |
|------------|--------------------------------|------------|
| scope      | `all`, `block`, `line`, `none` | string     |

## Document

- GitHub pages: [https://jiovan-labs.github.io/babel-plugin-remove-comment](https://jiovan-labs.github.io/babel-plugin-remove-comment)

## References

- [AST Explorer](https://astexplorer.net)
- [Babel AST Spec](https://github.com/babel/babel/blob/master/packages/babel-parser/ast/spec.md)
- [Babel repl](https://babeljs.io/repl)
- [Babel Plugin Handbook](https://github.com/jamiebuilds/babel-handbook/blob/master/translations/en/plugin-handbook.md)

## License

This project is under the [MIT License](https://mit-license.org/).

## Copyright

Beijing Jiovan Technology Ltd.

## Website

- Jiovan: [https://jiovan.com](https://jiovan.com)
