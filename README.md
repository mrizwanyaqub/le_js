le.js
=====

Client-side JavaScript library for [Logentries](http://www.logentries.com).

Features
--------

* Small- ~1.6k (minified)
* Cross-browser compatible
* No external dependencies
* Simple API

le.js allows your desktop & mobile web apps to submit logging events to Logentries.

Usage
-----

* Get the latest library build [here](https://github.com/logentries/le_js/releases/download/v0.1/le.min.js) or download a [full release](https://github.com/logentries/le_js/releases).

* Include the library in your page:

```html
<html lang="en">
  <head>
    <title>your page</title>
    <script src="/js/le.min.js"></script>
    <script>
      // Create a log stream...
      var stream = LE.init({token: 'YOUR-TOKEN'});
      // ...and log some events!
      stream.log("Hello, logger!");
    </script>
  </head>
  ...

```

Get a free [account](https://logentries.com/quick-start/) if you don't already have one.