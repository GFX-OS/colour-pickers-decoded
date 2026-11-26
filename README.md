# Colour Pickers Decoded

A short, playful course on colour for the web, guided by Huey. It walks through the colour wheel, hue, hex codes, RGB, HSB and HSL, then lets you build a palette for a small website.

Live at [andresramirez.design/colour-pickers-decoded](https://andresramirez.design/colour-pickers-decoded).

Made by [Andres Ramirez](https://www.linkedin.com/in/andresramirezdesign/).

## How it's used

The Webflow page holds one embed:

```html
<div id="cpd-mount"></div>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/GFX-OS/colour-pickers-decoded@v1.0.0/dist/cpd.css">
<script src="https://cdn.jsdelivr.net/gh/GFX-OS/colour-pickers-decoded@v1.0.0/dist/cpd.js"></script>
```

Each release gets a new tag, and the embed points at that tag.
