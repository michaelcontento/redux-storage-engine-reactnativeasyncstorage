# [redux-storage-engine-reactnativeasyncstorage][]

[![build](https://travis-ci.org/michaelcontento/redux-storage-engine-reactnativeasyncstorage.svg?branch=master)](https://travis-ci.org/michaelcontento/redux-storage-engine-reactnativeasyncstorage)
[![dependencies](https://david-dm.org/michaelcontento/redux-storage-engine-reactnativeasyncstorage.svg)](https://david-dm.org/michaelcontento/redux-storage-engine-reactnativeasyncstorage)
[![devDependencies](https://david-dm.org/michaelcontento/redux-storage-engine-reactnativeasyncstorage/dev-status.svg)](https://david-dm.org/michaelcontento/redux-storage-engine-reactnativeasyncstorage#info=devDependencies)

[![license](https://img.shields.io/npm/l/redux-storage-engine-reactnativeasyncstorage.svg?style=flat-square)](https://www.npmjs.com/package/redux-storage-engine-reactnativeasyncstorage)
[![npm version](https://img.shields.io/npm/v/redux-storage-engine-reactnativeasyncstorage.svg?style=flat-square)](https://www.npmjs.com/package/redux-storage-engine-reactnativeasyncstorage)
[![npm downloads](https://img.shields.io/npm/dm/redux-storage-engine-reactnativeasyncstorage.svg?style=flat-square)](https://www.npmjs.com/package/redux-storage-engine-reactnativeasyncstorage)

`AsyncStorage` based engine for [redux-storage][].

# Moved to the react-stack organisation

My focus has left the node / react ecosystem and this module has got a new home
over at [react-stack](https://github.com/react-stack/redux-storage-engine-reactnativeasyncstorage)!

## Installation

    npm install --save redux-storage-engine-reactnativeasyncstorage

## Usage

This will use `AsyncStorage` out of [react-native][].

```js
import createEngine from 'redux-storage-engine-reactnativeasyncstorage';
const engine = createEngine('my-save-key');
```

## License

    The MIT License (MIT)

    Copyright (c) 2015 Michael Contento

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
    the Software, and to permit persons to whom the Software is furnished to do so,
    subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
    FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
    IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

  [redux-storage]: https://github.com/michaelcontento/redux-storage
  [redux-storage-engine-reactnativeasyncstorage]: https://github.com/michaelcontento/redux-storage-engine-reactnativeasyncstorage
  [react-native]: https://facebook.github.io/react-native/
