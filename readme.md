# ios-deliver [![Build Status](https://travis-ci.org/stephanebachelier/ios-deliver.svg?branch=master)](https://travis-ci.org/stephanebachelier/ios-deliver)

## Notice

Currently in heavy development..

> My bedazzling module


## Install

```
$ npm install --save ios-deliver
```


## Usage

```js
const deliver = require('ios-deliver');

deliver('unicorns');
//=> 'unicorns & rainbows'
```


## API

### deliver(input, [options])

#### input

Type: `string`

Lorem ipsum.

#### options

##### foo

Type: `boolean`  
Default: `false`

Lorem ipsum.


## CLI

```
$ npm install --global ios-deliver
```

```
$ ios-deliver --help

  Usage
    ios-deliver [input]

  Options
    --foo  Lorem ipsum. [Default: false]

  Examples
    $ ios-deliver
    unicorns & rainbows
    $ ios-deliver ponies
    ponies & rainbows
```


## License

MIT © [Stéphane Bachelier](http://github.com/stephanebachelier)
