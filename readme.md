# Performance Checklist

## Table of Contents

*   [Miscellaneous](#miscellaneous)
*   [Audits](#audits)
*   [HTTP optimisation](#http-optimisation)
    *   [HTTP/1](#http1)
    *   [HTTP/2](#http2)
*   [Caching](#caching)
*   [Minification](#minification)
    *   [Images](#images)
    *   [CSS](#css)
    *   [HTML](#html)
    *   [JavaScript](#javascript)
    *   [Fonts](#fonts)
*   [Perceived Performance](#perceived-performance)
*   [Performance](#performance)
    *   [Images](#images-1)
    *   [CSS](#css-1)
    *   [HTML](#html-1)
    *   [JavaScript](#javascript-1)
    *   [Fonts](#fonts-1)
*   [Backend optimisation](#backend-optimisation)

## Miscellaneous

*   Tip: Different profile / user in Chrome without extensions
*   Add some more points here...

## Audits

*   Add some more points here...

## HTTP optimisation

*   Add some more points here...

### HTTP/1

*   Add some more points here...

### HTTP/2

*   Add some more points here...

## Caching

*   Add some more points here...

## Minification

*   Add some more points here...

### Images

*   Images as WebP:
    Change the images to .webp instad of .jpg (of .png).

    ```
    <picture>
      <source type="image/webp" srcset=“l.webp" media="(min-width: 640px)">  <source type="image/webp" srcset="m.webp" media="(min-width: 320px)">
      <source type="image/webp" srcset="s.webp">
      <source srcset="l.jpg" media="(min-width: 640px)">  <source srcset="m.jpg" media="(min-width: 320px)">
      <source srcset="s.jpg">
      <img alt="Description of the image" src="l.jpg">
     </picture>
     ```

		 ![alt text](https://github.com/s44s/performance-matters-checklist/blob/master/first.png "Logo Title Text 1")

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Perceived Performance

*   Add some more points here...

## Performance

*   Add some more points here...

### Images

*   Add some more points here...

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Backend optimisation

*   Add some more points here...
