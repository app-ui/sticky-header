# APP UI: Sticky Header

Web Component using Polymer that updates a collection to display headers in a fixed position (while relevant).


## Examples

* [Static](http://rawgit.com/app-ui/stickyheader/master/examples/static.html)


## Install

Using bower:
```
bower install app.ui.stickyheader
```


## Usage

1. Import Web Components' polyfill:

```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/platform.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/polymer.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/app.ui.stickyheader/src/component.html">
```

3. Start using it!

```html
<div is="sticky-header"></div>
```

Currently the component extends the ```<div>``` tag.


## Options

This is a direct extension of the [Backbone UI component](http://github.com/backbone-ui/sticky-header) with the same name. Its options are defined as ```option-``` parameters in the tag, for example:
```
<div is="sticky-header" option-itemEl=".headerclass" option-offset="100">...</div>
```


## Credits

Initiated by Makis Tracend ( [@tracend](http://github.com/tracend) )

Distributed through [Makesites.org](http://makesites.org)


## License

Released under the [MIT License](http://makesites.org/licenses/MIT)
