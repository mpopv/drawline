# drawline

A Sass mixin that generate an inline SVG background images by drawing a line with an ASCII art syntax similar to `grid-template-areas`. Ideal for generating simple decorative shapes like chevrons or arrows.

# Installation

```
npm i -D drawline
```

# Usage

```scss
@import '../../node_modules/drawline/drawline';

// A right-facing chevron
.right-chevron {
  background-image: drawline(
    ('-1---' // A Sass list of ASCII art strings
     '-----'
     '---2-'
     '-----'
     '-3---'),
    #ff0000, // The stroke color of the line
    1,       // The stroke width of the line
    false    // Whether the last point should connect to the first
  );
}
```
