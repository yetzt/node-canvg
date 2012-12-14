# node-canvf

A nodejs port of canvg
http://code.google.com/p/canvg/

## Usage
```` js
var canvg = require("./lib/canvg");
var Canvas = require("canvas");

var canvas = new Canvas(640,480);

canvg(canvas, '<svg>...</svg>');

/* and so on */

````

## Todo

The canvg code is pretty much untouched. A lot of browser-specific code has to be removed or rewritten.
