# sircus-tools-gutter-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-gutter-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-gutter-responsive)

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-gutter-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-gutter-responsive";
/*
@import "sircus-tools-gutter-responsive/lib/sm-gutter.css";
@import "sircus-tools-gutter-responsive/lib/md-gutter.css";
@import "sircus-tools-gutter-responsive/lib/lg-gutter.css";
*/
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-gutter-responsive/converted";
// @import "./node_modules/sircus-tools-gutter-responsive/scss/sm-gutter";
// @import "./node_modules/sircus-tools-gutter-responsive/scss/md-gutter";
// @import "./node_modules/sircus-tools-gutter-responsive/scss/lg-gutter";
```


> html

```html
<div class="t-sm-gutter"></div>
<div class="t-sm-gutterReset"></div>
<div class="t-sm-gutter2x"></div>
<div class="t-sm-gutter2xReset"></div>

<div class="t-md-gutter"></div>
<div class="t-md-gutterReset"></div>
<div class="t-md-gutter2x"></div>
<div class="t-md-gutter2xReset"></div>

<div class="t-lg-gutter"></div>
<div class="t-lg-gutterReset"></div>
<div class="t-lg-gutter2x"></div>
<div class="t-lg-gutter2xReset"></div>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
