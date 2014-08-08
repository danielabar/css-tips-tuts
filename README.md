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

## Style Placeholder Text

[Demo](http://danielabar.github.io/css-tips-tuts/placeholder.html)

New attribute introduced with HTML5. Used to specify a temporary text value inside an input field.

Requires vendor prefixes to style it.

## Remove Dotted Outline on Links

[Demo](http://danielabar.github.io/css-tips-tuts/dottedoutline.html)

When user tabs through links, a faint dotted border appears around them. This can be removed with styling.

BUT outline is important for accessibility, so think twice before removing it.

Outline also applies to text inputs having focus. This can also be removed.

## Create custom radio buttons and checkboxes

[Demo](http://danielabar.github.io/css-tips-tuts/customradio.html)

First hide the element so that a custom one can be created.

Then use `:before` pseudo element of the label to create a styled checkbox.

To make the styled element have a checkbox when user clicks, use the `:checked` pseudo class.

## Create Awesome States on Form Elements

[Demo](http://danielabar.github.io/css-tips-tuts/formstates.html)

Start by creating a reset for the form, then style the `:hover` and `:focus` states.

## Horizontal and Vertical Centering

[Demo](http://danielabar.github.io/css-tips-tuts/centering.html)

There are three kinds of centering

1. Centering lines of text
2. Centering a block of text or an image
3. Centering a block of text or an image vertically

Note that images display `inline` by default. To do centering, must set `display: block`.

For vertical align, must set a height.

## Absolutely Center an Image

[Demo](http://danielabar.github.io/css-tips-tuts/imgcentering.html)

Placing an image in the middle of its parent element.

There are two techniques to achieve this.

First method uses `background` css property with url reference to image.

Second method uses absolute positioning. Any element can be positioned this way, not just images.
As long as the element has a width, height and is capable of receiving margins.

## Absolutely Center an Image