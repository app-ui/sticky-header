# APP UI: Sticky Header

Web Component using Polymer that updates a collection to display headers in a fixed position (while relevant).


## Examples

* [Static](http://rawgit.com/app-ui/stickyheader/master/examples/static.html)


## Dependencies

This component relies on the following third-party libraries:

* [APP](http://makesites.org/projects/app)
* [jQuery](http://jquery.com)
* [Underscore](http://underscorejs.org)


## Install

Download the component and extract in 'components/app-ui-sticky-header'
```
cd [project folder]
wget https://github.com/app-ui/sticky-header/archive/master.zip
unzip master.zip -d ./components/
```

Using bower: (Old method)
```
bower install app.ui.stickyheader
```


## Usage

The component is built on top of [APP](http://makesites.org/projects/app) which should be loaded before the component in the <head> section of your website. This library uses the non-standard method of "html imports" for loading custom elements. 


1. Include APP library

```html
<script src="components/app/build/app.min.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="components/app-ui-sticky-header">
```

3. Start using it!

```html
<div is="app-ui-sticky-header"></div>
```
Currently the component extends the ```<div>``` tag.


## Options

This is a direct extension of the [Backbone UI component](http://github.com/backbone-ui/sticky-header) with the same name. Its options are defined as ```option-``` parameters in the tag, for example:
```
<div is="sticky-header" option-itemEl=".headerclass" option-offset="100">...</div>
```

These are the set of options you can use as attributes in your custom element:

...


## Events

...



## Credits

Initiated by Makis Tracend ( [@tracend](http://github.com/tracend) )

Distributed through [Makesites.org](http://makesites.org)


### License

Released under the [MIT License](http://makesites.org/licenses/MIT)


