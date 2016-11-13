# Typed serve-static
[![Build Status](https://travis-ci.org/types/npm-serve-static.svg?branch=master)](https://travis-ci.org/types/npm-serve-static)

Typescript Typings for [serve-static](https://www.npmjs.com/package/serve-static).

## Installation
```sh
typings install --save serve-static
```

## Usage

```ts
import express = require('express');
import serveStatic = require('serve-static');
 
const app = express();
 
app.use(serveStatic('public/ftp', {index: ['default.html', 'default.htm']}));
app.listen(3000);
```

---------------------------------------

_Based on the typings by [Uros Smolnik](https://github.com/urossmolnik) on [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped)_
