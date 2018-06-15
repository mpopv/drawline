# drawline

A Sass mixin that generates inline SVG background images by drawing simple shapes with an ASCII art syntax similar to `grid-template-areas`.

⚠️ WIP ⚠️: Currently this will probably break when used for anything more complex than a single line or left- or right-facing chevron.

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
    ('-x---'
     '-----'
     '---x-'
     '-----'
     '-x---'),
    #ff0000
  );
}
```
