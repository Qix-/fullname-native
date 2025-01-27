# fullname-native [![Build Status](https://travis-ci.org/sindresorhus/fullname-native.svg?branch=master)](https://travis-ci.org/sindresorhus/fullname-native)

> Get the fullname of the current user


## Install

```
$ npm install --save fullname-native
```

**This is a [native binding](http://nodejs.org/api/addons.html) and expects you to have the required [toolchain](https://github.com/nodejs/node-gyp#installation).** *(ignore the node-gyp install)*

Tested to work on OS X, Linux and Windows.


## Usage

```js
const fullname = require('fullname-native');

console.log(fullname);
//=> 'Sindre Sorhus'
```


## Related

- [fullname-cli](https://github.com/sindresorhus/fullname-cli) - CLI for this module
- [fullname](https://github.com/sindresorhus/fullname) - Non-native version of this module
- [username](https://github.com/sindresorhus/username) - Get the username of the current user


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
