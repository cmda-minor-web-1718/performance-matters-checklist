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

*   The optimalisation off the visual progress is terrible. The website does not show any content till every content is loaded. This problem leads up to a huge visaul progress area. 
![Visual Progress CMD Amstedam](https://raw.githubusercontent.com/dipsaus9/performance-matters-checklist/master/visual%20progress%20cmd%20amsterdam.png)

## HTTP optimisation

*   Add some more points here...

### HTTP/1

*   All files are being loaded by a HTTP1 request. This is not a big problem unless you are loading a lot of files separately. In the website there are a lot of css and js files being loaded. HTTP1 can only request a maximum of request at one time. This means this procces will take a lot longer. 
![Request CMD Amsterdam](https://raw.githubusercontent.com/dipsaus9/performance-matters-checklist/master/73aee4dda5a82919ab88d80fb735fb79.png)

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

*   Add some more points here...

### Fonts

*   Add some more points here...

## Perceived Performance

*   Add some more points here...

## Performance

*   Add some more points here...

### Images

*   Images are not being serverd by WebP. This means all images that are being loaded on the website take up to 10.510 seconds (total of 1.8MB).

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
