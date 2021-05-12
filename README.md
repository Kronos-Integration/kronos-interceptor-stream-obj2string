[![npm](https://img.shields.io/npm/v/@kronos-integration/interceptor-stream-obj2string.svg)](https://www.npmjs.com/package/@kronos-integration/interceptor-stream-obj2string)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![minified size](https://badgen.net/bundlephobia/min/@kronos-integration/interceptor-stream-obj2string)](https://bundlephobia.com/result?p=@kronos-integration/interceptor-stream-obj2string)
[![downloads](http://img.shields.io/npm/dm/@kronos-integration/interceptor-stream-obj2string.svg?style=flat-square)](https://npmjs.org/package/@kronos-integration/interceptor-stream-obj2string)
[![GitHub Issues](https://img.shields.io/github/issues/Kronos-Integration/interceptor-stream-obj2string.svg?style=flat-square)](https://github.com/Kronos-Integration/interceptor-stream-obj2string/issues)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FKronos-Integration%2Finterceptor-stream-obj2string%2Fbadge&style=flat)](https://actions-badge.atrox.dev/Kronos-Integration/interceptor-stream-obj2string/goto)
[![Styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Known Vulnerabilities](https://snyk.io/test/github/Kronos-Integration/interceptor-stream-obj2string/badge.svg)](https://snyk.io/test/github/Kronos-Integration/interceptor-stream-obj2string)
[![Coverage Status](https://coveralls.io/repos/Kronos-Integration/interceptor-stream-obj2string/badge.svg)](https://coveralls.io/github/Kronos-Integration/interceptor-stream-obj2string)

# kronos-interceptor-stream-obj2string

Splits a stream into lines.

# API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

*   [Transform](#transform)
*   [constructor](#constructor)
    *   [Parameters](#parameters)
*   [\_transform](#\_transform)
    *   [Parameters](#parameters-1)
*   [Stream2ObjectInterceptor](#stream2objectinterceptor)

## Transform

Transforms an object stream into a stream of strings

## constructor

Creates the line parser and sets the options.
The following options are supported:
{
"allow_new_line_in_cell" : true,
"line_separator" : "\n",
"quote_char" : '"'
"skip_empty_lines" : true
}

### Parameters

*   `opts`   (optional, default `{}`)

## \_transform

Reads the stream data and split it into lines.

### Parameters

*   `data`  
*   `enc`  
*   `next`  

## Stream2ObjectInterceptor

**Extends Interceptor**

This interceptor cares about the handling of the messages.
It will add the hops and copies the messages

# install

With [npm](http://npmjs.org) do:

```shell
npm install kronos-interceptor-stream-obj2string
```

# license

BSD-2-Clause
