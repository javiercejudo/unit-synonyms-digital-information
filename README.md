# unit-synonyms-digital-information

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-digital-information.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-digital-information)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-digital-information/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-digital-information?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-digital-information/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-digital-information)

Digital information units synonyms

## Install

    npm i unit-synonyms-digital-information

## Units

- [Byte](https://en.wikipedia.org/wiki/Byte)
- [Bit](https://en.wikipedia.org/wiki/Bit)
- [Kibibyte](https://en.wikipedia.org/wiki/Kibibyte)
- [Mebibyte](https://en.wikipedia.org/wiki/Mebibyte)
- [Gibibyte](https://en.wikipedia.org/wiki/Gibibyte)
- [Tebibyte](https://en.wikipedia.org/wiki/Tebibyte)
- [Pebibyte](https://en.wikipedia.org/wiki/Pebibyte)
- [Exbibyte](https://en.wikipedia.org/wiki/Exbibyte)
- [Zebibyte](https://en.wikipedia.org/wiki/Zebibyte)
- [Yobibyte](https://en.wikipedia.org/wiki/Yobibyte)

## Usage

```js
var synonyms = require('unit-synonyms-digital-information').synonyms;

synonyms['b']; // => bit
synonyms['B']; // => byte
synonyms['GiB']; // => gibibyte
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
