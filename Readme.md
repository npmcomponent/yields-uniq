*This repository is a mirror of the [component](http://component.io) module [yields/uniq](http://github.com/yields/uniq). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-uniq`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# Uniq

  Remove repeated elements of an Array

## Installation

```
$ npm install uniq-component
$ component install yields/uniq
```

## API

### uniq(arr)

```js
var uniq = require('uniq');
var arr = [1, 2, 3, 1, 2, 3, 1, 2, 3];
uniq(arr); // -> [1, 2, 3]
```

### uniq(arr, select)

```js
var uniq = require('uniq');
var arr = [1, 2, 3, 1, 2, 3, 1, 2, 3];
uniq(arr, [1, 3]); // // remove specific elements -> [1, 2, 3, 2, 2]
```

## Tests

Download testing dependecies

```
npm install
```

Run tests

```
make test
```

## License

  MIT
