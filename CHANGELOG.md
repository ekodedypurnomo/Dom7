# Change Log

## Dom7 v1.6.3 - Released on May 30, 2017
  * Added shortcut methods `click blur focus focusin focusout keyup keydown keypress submit change mousedown mousemove mouseup mouseenter mouseleave mouseout mouseover touchstart touchend touchmove resize scroll`

## Dom7 v1.6.2 - Released on May 12, 2017
  * Proxified events. Now all events are being added/removed using proxy functions. This allows to pass additional arguments to events handlers and detach all assigned event listener by calling e.g. `$$(document).off('someEvent');`

## Dom7 v1.6.1 - Released on April 19, 2017
  * New `Dom7.extend(obj1, obj2, ...)` method
  * Added `.animate(props, params)` and `.stop()` animation methods
  * Added ES2015 module build
