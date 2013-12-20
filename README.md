# l-flexbox

l-flexbox.css is a CSS utility class to help you quickly build complex
layouts using `flexbox`.

l-flexbox.css supports a `float` fallback for browsers that don't support
the flexbox spec.

[Checkout the demo](http://htmlpreview.github.io/?https://github.com/ronadamsjr/l-flexbox-css/blob/master/demo.html)

## What does it do?

* Allows you to quickly start using CSS3 flexbox for layouts.
* Gives you sensible default fallback support in older browsers.
* Encourages (but does not enforce) [BEM-style CSS](http://bem.info/method/) conventions.
* Provides easy hooks for extensibility.
* Explains what the code does using detailed comments.

## Dependencies

[Modernizr](https://github.com/Modernizr/Modernizr)

## How to Install
* Install with [Bower](http://bower.io/): `bower install --save l-flexbox-css`
* Download from the [project page](https://github.com/ronadamsjr/l-flexbox-css).

## How to use it

Include l-flexbox.css in your HTML HEAD.

Create a "flexbox" container element, add the `l-flexbox` class to this element.
Create child-elements and add the `l-flexbox--item` class to these elements.

```html
<div class="l-flexbox">
    <div class="l-flexbox--item" style="border:1px solid blue;">First flex item</div>
    <div class="l-flexbox--item" style="border:1px solid green;">Second flex item</div>
</div>
```

## Authors

* [Ron. Adams](https://github.com/ronadamsjr) - [@ronaldjadams](http://twitter.com/ronaldjadams)
* Created at [Nara Logics](http://nara.me/)

## Licence

Copyright 2013 Nara Logics, Inc.

Licensed under the MIT License
