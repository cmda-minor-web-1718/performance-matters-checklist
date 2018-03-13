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
*   The optimalisation of the visual progress is terrible.
    The website does not show any content till every content is loaded.
    This problem leads up to a huge visaul progress area. 
    ![Visual Progress CMD Amstedam](https://raw.githubusercontent.com/dipsaus9/performance-matters-checklist/master/visual%20progress%20cmd%20amsterdam.png)

## HTTP optimisation

*   Add some more points here...

### HTTP/1

*   Add some more points here...
*   All files are being loaded by a HTTP1 request.
    This is not a big problem unless you are loading a lot of files separately.
    In the website there are a lot of css and js files being loaded.
    HTTP1 can only request a maximum of request at one time.
    This means this procces will take a lot longer.
    ![Request CMD Amsterdam](https://raw.githubusercontent.com/dipsaus9/performance-matters-checklist/master/73aee4dda5a82919ab88d80fb735fb79.png)

### HTTP/2

*   Add some more points here...
*   [Enable HTTP2](https://tools.keycdn.com/http2-test)

## Caching

*   Add some more points here...
*   Leverage browser caching.

## Minification

*   Add some more points here...

### Images

*   Change image extensions(web-p or JPEG XR)
*   Change image file sizes
*   Add some more points here...
*   Compress images
*   Optimise image sizes

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...
*   Minify the Javascript: You could do this manually by going to [js compress](https://jscompress.com/) but you could use Gulp or any taskworker that can use UglifyJS. Minification removes unnecessary data and unnecessary spaces and misc. To improve the loadspeed and a small decrease in size.
*   Parse JavaScript using Defer.

### Fonts

*   Add some more points here...

## Perceived Performance

*   Add some more points here...

## Performance

*   Add some more points here...

### CDN

*   Because this website is also focused on international student it's recommended to use a CDN.
    The load-time will decrease for users outside the NL — Source:
    [CDN-REPORT](http://www.whatsmycdn.com/?uri=https%3A%2F%2Fwww.cmd-amsterdam.nl%2F&location=NA)

### Images

*   Add some more points here...
*   Images are not being serverd by WebP.
    This means all images that are being loaded on the website take up to 10.510 seconds (total of 1.8MB).

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...
*   Make use of `<script src="index-6a14b2.js" defer></script>` to load your javascript after the DOM has been rendered. Load early, execute after the DOM is ready. You could do this conditionally via [@filamentgroup](https://github.com/filamentgroup/loadJS)

### Fonts

*   Add some more points here...
*   Content isn't being loaded because of the font. It takes a long time. After 29 seconds. You could use `font-display: swap;`. But on [CanIUse.com](https://caniuse.com/#search=font-display) it's not really that supported. Best way todo this is probably store your font in the cookies. You load the fallback in first and when you stored the font in the Cookies you just swap the font to the main font. This is what this does `font-display: swap;` but the latter way is more supported.

## Backend optimisation

*   Add some more points here...
*   There are multiple things being loaded and not used. Alot of the Woocommerce scripts are being loaded and it takes priority for some reason. But it isn't used. [Google page speeds](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fwww.cmd-amsterdam.nl%2F) the examples are a cart.js alot of css etc.  
