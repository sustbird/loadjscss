# Dynamic CSS and JS loader

This small utility (minified version is ~747 bytes only!) will help to load css and js files dynamically/asynchronously.

###Features:
  - Load css files from server
  - Loads js files from server
  - Apply callback method after css/js file are loaded
  - Support to add media for css
  - Guarding against duplicate file loading from server(include id)

### Version
1.0.0

### Installation
##### Manually
Download the loadjscss.js file from here and include in your html.
```sh
<script type="application/javascript" src="loadjscss.js"></script>
```

##### Through Bower
Download via bower
```sh
$ bower install loadjscss
```
and then add in your html
```sh
<script type="application/javascript" src="bower_components/loadjscss/loadjscss.js"></script>
```
### API Doc
[See here](loadjscss.md)

### Files Included:
* loadjscss.js [main library file]
* index.html [test html file]
* loadjscss.md [api doc file]

### Development

Want to contribute? Great! Code and create a pull request
License
----

MIT

