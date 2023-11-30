# npm package example

> This is a npm package example

[![npm version](https://img.shields.io/npm/v/@rkunihiro/hello.svg?style=flat-square)](https://www.npmjs.com/package/@rkunihiro/hello)
[![npm downloads](https://img.shields.io/npm/dm/@rkunihiro/hello.svg?style=flat-square)](https://www.npmjs.com/package/@rkunihiro/hello)
[![GitHub stars](https://img.shields.io/github/stars/rkunihiro/npm-hello.svg?style=flat-square)](https://github.com/rkunihiro/npm-hello)

## Overview

Show "Hello,World!"

## Installation

```shell
# Locally
npm i @rkunihiro/hello

# Globally
npm i -g @rkunihiro/hello
```

## Usage

### Command line

```shell
# Show "Hello,World!"
./node_modules/.bin/hello

# Show "Hello,World!"
npx hello
```

### API

**_CommonJS_**

```js
const { message } = require("@rkunihiro/hello");

console.log(message()); // Show "Hello,World!"
```

**_ES Modules_**

```js
import { message } from "@rkunihiro/hello";

console.log(message()); // Show "Hello,World!"
```
