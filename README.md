# jQuery Timer Plugin
A simple and effective way of handling JavaScript internals using jQuery.

## Creating a new timer
Timers are created with an easy to remember syntax.

    var timer = $.timer(timeout, callback);

- `timeout` is the time to set the interval to run at, in milliseconds.

The callback option can obviously be either a reference to another function, or an anonymous function.

## Timer methods
In the chance that you need to stop or reset your timer, you can use the following two methods:
- `.stop()`
- `.reset([timeout])`

The timeout option for `reset` is optional, as it'll use the default internal option `reset`.

## License
jQuery Timer Plugin is licensed under the MIT License.
