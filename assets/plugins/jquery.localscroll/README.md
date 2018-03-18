# jQuery.localScroll

### Installation and usage

Using [bower](https://github.com/twitter/bower):
```bash
bower install jquery.localScroll
```

### Downloading Manually

If you want the latest stable version, get the latest release from the [releases page](https://github.com/flesler/jquery.localScroll/releases).

### jQuery.scrollTo

This plugin requires [jQuery.scrollTo](http://github.com/flesler/jquery.scrollTo).
In order to use jQuery.scrollTo 2.0 you need to update jQuery.localScroll to 1.4.0 and above.

### Notes

* The hash of settings is passed in to jQuery.scrollTo, so, in addition to jQuery.localScroll's settings, you can use any of jQuery.scrollTo's. Check that plugin's documentation for further information.

* If you want to convert the links from ALL over the page, with the same settings, just call $.localScroll(...) instead of $(...).localScroll(...)

* Most of this plugin's defaults, belong to jQuery.scrollTo, check it's demo for an example of each option.