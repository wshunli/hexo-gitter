# hexo-gitter

[![Gitter](https://badges.gitter.im/wshunli/hexo-gitter.svg)](https://gitter.im/wshunli/hexo-gitter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![npm](https://img.shields.io/npm/v/hexo-gitter.svg)](https://www.npmjs.com/package/hexo-gitter)
[![Travis](https://img.shields.io/travis/wshunli/hexo-gitter.svg)](https://travis-ci.org/wshunli/hexo-gitter)
[![GitHub license](https://img.shields.io/github/license/wshunli/hexo-gitter.svg)](https://github.com/wshunli/hexo-gitter)
[![David](https://img.shields.io/david/wshunli/hexo-gitter.svg)](https://github.com/wshunli/hexo-gitter)
[![David](https://img.shields.io/david/dev/wshunli/hexo-gitter.svg)](https://github.com/wshunli/hexo-gitter)

A generator for Hexo that adds [Gitter](https://gitter.im) to every page.

## Install

``` bash
$ npm install hexo-gitter --save
```

## Usage

Add the hexo-gitter to your theme template

``` JavaScript
<%- gitter('RoomName') %>
```

`RoomName` represents Gitter's room, which can be found on the Gitter website

## Examples

``` JavaScript
<%- gitter('wshunli/hexo-gitter') %>
```

## License

    MIT License

    Copyright (c) 2018 wshunli

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.