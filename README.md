# jquery.splitter.js

Simple splitter for jquery

[DEMO](http://shunjikonishi.github.io/jquery-splitter/demo.html)

## Install

``` bash
npm install jquery-simple-splitter
```

## Usage
Simple horizontal split is like this.

``` javascript
<script>
$(function() {
  $("#workspace").splitter({
    "orientation": "horizontal",
    "limit": 100
  });
});
</script>
```

The target element must have only two elements. And must not have other.

See [demo.html](demo.html)

## Settings
- orientation - "horizontal" or "vertical". If omitted, default is "horizontal"
- limit - int. Minimum size of left(top) element.
- keepLeft - boolean. When window resized, keep left(top) size or not.
