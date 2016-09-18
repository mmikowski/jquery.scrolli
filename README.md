# jquery.scrolli.js
## Overview

`jquery.scrolli.js` provides simple scroll indicators.
Please see `index.html` for an example implementation.

## Methods
```js
// Add a jQuery collection
$.scrolli.add$List( $scrolling_divs );

// Recalculate scroll indicators.  Useful after a window resize.
$.scrolli.recalc$All();

// Remove a jQuery collection
$.scrolli.rm$List( $others_divs );

// Remove all scrolli elements
$.scrolli.reSet();

```

## How it works
Scrolli simply adds a class to an element if it is substantially scrolled down
(a "top content indicator"), and adds a different class if there is content
below the bottom edge of the scroll area (a "bottom content indicator").
The top indicator class is 'scrolli-top-in' and the bottom indicator class is
'scrolli-btm-on'.  These are easly changed by modifying the file.

## Compatibility
Should work on all browsers supported by jQuery 3.

## Release Notes

### Copyright (c)
2016 Michael S. Mikowski (mike[dot]mikowski[at]gmail[dotcom])

### License
MIT

### Version 1.x
- First "public release" versions with a working example.

## End
