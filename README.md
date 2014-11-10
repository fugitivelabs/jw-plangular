# jw-plangular
============

A simple Angular directive for JW-Player that works with ng-repeat

## Dependencies
- required:   
  [angularjs](http://angularjs.org/)
- required: 
  [jwplayer](http//jwplayer.com)

## Install 
1. Copy or download the jw-plangular.min.js file to your project. 
2. Reference the file in your html 
3. Include the module in angular (i.e. in `app.js`) as `JwPlangular`

## Documentation 
Reference jw-plangular in your HTML after angular and before your project app. 

```html

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/angularjs/1.2.23/angular.js"></script>
<script type="text/javascript" src="jw-plangular.min.js"></script>
<script type="text/javascript" src="app.js"></script>

```

Include the module in your angular.

```js

angular.module('myApp', [  
  "jw-plangular"
]);

```

### To use as single player in the page: