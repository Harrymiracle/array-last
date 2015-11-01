# array-last [![NPM version](https://badge.fury.io/js/array-last.svg)](http://badge.fury.io/js/array-last)

> Get the last or last n elements in an array.

## Install

```sh
$ npm i array-last --save-dev
```

## Usage

```js
var last = require('array-last');

last(['a', 'b', 'c', 'd', 'e', 'f']);
//=> 'f'

last(['a', 'b', 'c', 'd', 'e', 'f'], 1);
//=> 'f'

last(['a', 'b', 'c', 'd', 'e', 'f'], 3);
//=> ['d', 'e', 'f']
```

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on November 01, 2015._