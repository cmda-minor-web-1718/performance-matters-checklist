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

*   Add some more points here...

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Minify the Javascript: You could do this manually by going to [js compress](https://jscompress.com/) but you could use Gulp or any taskworker that can use UglifyJS. Minification removes unnecessary data and unnecessary spaces and misc. To improve the loadspeed and a small decrease in size.

### Fonts

*   


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

*   Content isn't being loaded because of the font. It takes a long time. After 29 seconds. You could use `font-display: swap;`. But on [CanIUse.com](https://caniuse.com/#search=font-display) it's not really that supported. Best way todo this is probably store your font in the cookies. You load the fallback in first and when you stored the font in the Cookies you just swap the font to the main font. This is what this does `font-display: swap;` but the latter way is more supported.

## Backend optimisation

*   Add some more points here...
