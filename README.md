# gopurs-datetime

## Local Go development

This checkout is part of the gopurs library family. Use the
[local Go development guide](../gopurs/README.md#develop-one-library-locally)
for toolchain setup, sibling dependencies, Spago configuration and Go commands.
The existing npm, Bower and Dhall commands below retain their JavaScript or
upstream roles.


[![Latest release](http://img.shields.io/github/release/purescript/purescript-datetime.svg)](https://github.com/purescript/purescript-datetime/releases)
[![Build status](https://github.com/purescript/purescript-datetime/workflows/CI/badge.svg?branch=master)](https://github.com/purescript/purescript-datetime/actions?query=workflow%3ACI+branch%3Amaster)
[![Pursuit](https://pursuit.purescript.org/packages/purescript-datetime/badge)](https://pursuit.purescript.org/packages/purescript-datetime)

Date and time types and functions.

## Installation

```
spago install datetime
```

## Documentation

This libary provides platform-independent representations of date and time. Parsing specific date formats, such as the ISO 8601 format, is the responsibility of other libraries, such as the [purescript-js-date](https://github.com/purescript-contrib/purescript-js-date) package. Likewise, writing a date/time type to string to display to humans is the responsibility of other libraries, such as the [purescript-formatters](https://github.com/slamdata/purescript-formatters) package.

Module documentation is [published on Pursuit](http://pursuit.purescript.org/packages/purescript-datetime).
