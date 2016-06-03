# \<range-slider\>

this is prototype of a range slider

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## How to attach custom events and use polymer gestures

Reference
[Events link](https://www.polymer-project.org/1.0/docs/devguide/events)
[Polymer gestures link](https://www.polymer-project.org/1.0/docs/devguide/gesture-events)


## Events supported

down and track equivalent to click and drag

```javascript
var slider = this.$.slider;
slider.addEventListener('down', function(){
var currentValue = this.value;
//do something
});
slider.addEventListener('track', function(){
var currentValue = this.value;
//do something
});
```

