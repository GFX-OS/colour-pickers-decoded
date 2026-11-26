# Colour Pickers Decoded

A short, playful course on colour for the web, guided by Huey. It walks through the colour wheel, hue, hex codes, RGB, HSB and HSL, then lets you build a palette for a small website.

Live at [andresramirez.design/colour-pickers-decoded](https://andresramirez.design/colour-pickers-decoded).

Made by [Andres Ramirez](https://www.linkedin.com/in/andresramirezdesign/).

## How it's used

The Webflow page holds one embed:

```html
<div id="cpd-mount"></div>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/GFX-OS/colour-pickers-decoded@<commit>/dist/cpd.css">
<script src="https://cdn.jsdelivr.net/gh/GFX-OS/colour-pickers-decoded@<commit>/dist/cpd.js"></script>
```

Each release is pinned by its commit, so the live page only changes when the embed is pointed at a new commit.
