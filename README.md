# enhanced-resolve

Offers a async require.resolve function. It's highly configurable.

[![Build Status](https://secure.travis-ci.org/webpack/enhanced-resolve.png?branch=master)](http://travis-ci.org/webpack/enhanced-resolve)

More documentation coming soon...

``` javascript
var resolve = require("enhanced-resolve");

resolve(string context, string identifier, object options, function callback(err, result))
resolve.sync(string context, string identifier, object options)
resolve.context(string context, string identifier, object options, function callback(err, result))
resolve.context.sync(string context, string identifier, object options)
```

*It is used in [webpack](/webpack/webpack)*