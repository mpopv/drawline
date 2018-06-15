# drawline

A Sass mixin that lets you draw simple shapes with ASCII art, and generates an inline SVG background image.

⚠️ WIP ⚠️ -- Currently this will probably break when used for anything more complex than a single line or left- or right-facing chevron.

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
