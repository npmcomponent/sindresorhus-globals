*This repository is a mirror of the [component](http://component.io) module [sindresorhus/globals](http://github.com/sindresorhus/globals). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/sindresorhus-globals`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# globals [![Build Status](https://travis-ci.org/sindresorhus/globals.svg?branch=master)](https://travis-ci.org/sindresorhus/globals)

> Global identifiers from different JavaScript environments

Extracted from [JSHint](https://github.com/jshint/jshint/blob/master/src/vars.js) and [ESLint](https://github.com/nzakas/eslint/blob/master/conf/environments.json) and merged.

It's just a [JSON file](globals.json), so use it in whatever environment you like.


## Install

Download [manually](https://github.com/sindresorhus/globals/releases) or with a package-manager.

```bash
$ npm install --save globals
```

```bash
$ bower install --save globals
```

```bash
$ component install sindresorhus/globals
```


## Usage

```js
var globals = require('globals');

console.log(globals.browser);
/*
{
	addEventListener: false,
	applicationCache: false,
	ArrayBuffer: false,
	atob: false,
	...
}
*/
```


## License

[MIT](http://opensource.org/licenses/MIT) © [Sindre Sorhus](http://sindresorhus.com)
