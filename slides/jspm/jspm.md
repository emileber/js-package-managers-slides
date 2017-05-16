## What about JSPM?

Frictionless browser package management that uses [SystemJS universal module loader](https://github.com/systemjs/systemjs).

```
$ npm install jspm
$ jspm install jquery
```

```
import $ from 'jquery'; // ES6-style import
var $ = require('jquery'); // CommonJS-style import
define(['jquery'], function($) { // AMD-style import
    // do whatever with jQuery here.
})
```