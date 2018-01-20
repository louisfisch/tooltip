# Tooltip
This is a SCSS written mixin that shapes an element into a tooltip.

## Usage
1. Download the `_tooltip.scss` file and move it into your main SCSS files' folder.
2. Add the line `@import "_tooltip";` at the beginning of each file in which you want to use the .

The mixin takes five optional arguments:

1. `$side` can be `top`, `right`, `bottom` or `left` (default is `top`).
2. `$arrow-width` is the arrow's width (default is `16px`).
3. `$position` is the tooltip's arrow position on the element's side in percent (default is `50%` i.e.: centered).
4. `$border-width` is the tooltip's border's width in pixels (default is `2px`).
5. `$border-color` is the tooltip's border's color (default is `red`).
3. `$background-color` is the color of the arrow and the background of the element (default is `tomato`).

Add the mixin to your element using `@include`:
```scss
section {
  @include tooltip(right, 24px);
}
```
This is just an example. You can include it in any element.

## Want to contribute?
This is just a start. Please feel free to fork and pull requests!
