# Border radius for iframes (like Google Maps Embed)
This is how you create rounded corners on an embedded iframe like Google Maps

Use the SVG below as a mask with the CSS property `mask-image` and change the rx/ry values to your preferred border radius.

```
<svg width="100%" height="100%" version="1.1"
  xmlns="http://www.w3.org/2000/svg">

  <rect width="100%" height="100%" rx="10" ry="10"
  style="fill:rgb(0,0,0);stroke-width:1;
  stroke:rgb(0,0,0)"/>
</svg>

```
