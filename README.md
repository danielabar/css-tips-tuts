# CSS Tips & Tricks

> Learning CSS with TutsPlus course [CSS Tips & Tricks](https://courses.tutsplus.com/courses/css-tips-tricks)

## Use CSS Shorthand

[Demo](http://danielabar.github.io/css-tips-tuts/css-shorthand.html)

Use shorthand syntax wherever possible for more consice, maintainable code.

For example, font, padding, margin, border, list-style.

## Change Text Selection Color

[Demo](http://danielabar.github.io/css-tips-tuts/text-selection.html)

Use to change the background highlight styling when text is selected.
Up until CSS3, this was not possible to style.

[Browser Support](http://caniuse.com/css-selection)

## Awesome Font Stacks

[Demo](http://danielabar.github.io/css-tips-tuts/font-stacks.html)

Specify a list of fonts. Then browser will pick first one that user has installed on their machine, reading from left to right.

## Drop Caps

[Demo](http://danielabar.github.io/css-tips-tuts/dropcaps.html)

To achieve old book effect where first letter of first paragraph is bigger than the rest.

First way to achieve this requires modifying markup with `<span>` tag, but is compatible with most browsers.

Second way to achieve this is using CSS3 pseudo selector `:first-letter` which is much cleaner because it doesn't clutter up the markup.
However it's not [supported](https://developer.mozilla.org/en-US/docs/Web/CSS/::first-letter#Browser_compatibility) in older browsers.