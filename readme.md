# hastscript-case-sensitive

[![NPM version](https://img.shields.io/npm/v/hastscript-case-sensitive?color=a1b858\&label=)](https://www.npmjs.com/package/hastscript-case-sensitive)

A fork of [hastscript](https://github.com/syntax-tree/hastscript), supporting for case-sensitive tagName.

`hastscript`'s `h` functions forced the tagName to be lowercase (introduced in [syntax-tree/hastscript#11](https://github.com/syntax-tree/hastscript/issues/11)). This fork removes the enforcement, and allows the tagName to be case-sensitive.

## Installation

```bash
npm i hastscript-case-sensitive
```

If you want to override the original `parse5` package, you can do it by adding the following to your `package.json`:

```json
{
  "resolutions": {
    "hastscript": "npm:hastscript-case-sensitive@7.1.2-0"
  }
}
```

## Versioning

This fork is planned to be kept in sync with the original `hastscript` package, the versioning will also be in sync with the main package, with an extra `-0` suffix indicating the patch versions of `hastscript-case-sensitive`.
