# Pwguide - angular visual validator for password input

## Installation

### With bower

Project is registered in bower registry only.

`bower install angular-pwguide`

### Add script and styles

```html
<script src="bower_components/angular-pwguide/pwguide.js"></script>
<link rel="stylesheet" href="bower_components/angular-pwguide/pwguide.css" />
```

## Usage

Activate module
```javascript
angular.module('app',[/* ... */ 'pwGuide']);
```

Use directive.

```html
<input pw-guide type="password">
```

## TODO

* watch for minlength change
* add support for setting list of tests by attribute

## Idea

Module inspired by Udacity Senior Web Developer Nanodegree materials.
