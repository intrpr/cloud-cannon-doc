---
title: Colour
category: General Inputs
details: |
  Input with dropdown for selecting colour.
  Displayed for keys ending in `_colour`, `_color`, `_rgb`, `_rgba`, `_hex`, `_hsv`, `_hsva`, `_hsl` and `_hsla`.
  Alternatively, you can use the variations without underscores as keys (e.g. `rgb` or `colour`).

  Each variation defines the preferred format of the colour. The `_colour` and `_color` variations default to hex.

  Variations ending in `a` have an additional transparency control.
yaml_code_block: |
  ---
  brand_colour: '#f05f40'
  ---
image_paths:
  - /images/editing/front-matter/colour.png
  - /images/editing/front-matter/colour-focus.png
info: Quote hex colours, otherwise the hash symbol begins a YAML comment.
---
