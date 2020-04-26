# Haffaz

[![NPM](https://img.shields.io/npm/v/haffaz.svg?style=flat-square) ](https://www.npmjs.com/package/haffaz)
[![Build Status](https://travis-ci.org/tomasbjerre/haffaz.svg?branch=master)](https://travis-ci.org/tomasbjerre/haffaz)

An example dictator created with [dictator-builder](https://github.com/tomasbjerre/dictator-builder).

## Usage

It can be used with any kind of repository, not only Node.

### Node

You can let **Haffaz** dictate your source repository by adding it to `package.json` like:

```json
{
  "scripts": {
    "prepare": "npx haffaz@a.b.c"
  }
}
```

### Other

It can be run from command line with: `npx haffaz@latest`.
