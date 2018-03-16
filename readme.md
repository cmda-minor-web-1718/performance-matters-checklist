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
*   Use the proper `lang`
*   Use a CDN

## Audits

*   The optimisation of the visual progress is terrible
    The website does not show any content till every content is loaded
    This problem leads up to a huge visual progress area

## HTTP optimisation

### HTTP/1

### HTTP/2

*   [Enable HTTP2](https://tools.keycdn.com/http2-test)

## Caching

*   Specify an expiration at least one week in the future for resources

## Minification

### Images

*   Compress images (such as with [PageSpeed Image Optimizer](https://i.onthe.io/google_speed))
*   Images with little detail and small colour pallet, are smaller with png format instead of jpg. If possible, use svg.

### CSS

*   Minify CSS

### HTML

*   Minify HTML

### JavaScript

*   Minify the JavaScript: either manually through
    [`jscompress`](https://jscompress.com/),
    [`minifier.org`](https://www.minifier.org/), or
    with something UglifyJS, potentially through Gulp

### Fonts

*   Add a fallback font
*   Use font subsetting

## Perceived Performance

*   Use a placeholder for background images (blurred/loading like) to
    indicate that here is and should be an image at that position

## Performance

### Images

*   Use newer image types (`.webp`; `.jxr` [jpg -> jxr](https://i.onthe.io/jxr))
*   Use inline images for the hero image instead of a background image
*   Add `srcset`s and `sizes`
*   Use [`<picture>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)s
*   Use (inline) `svg` when possible
*   Serve images in a proper size
    This will improve load time and save cellular data
    If you provide images larger than the user needs, you are just wasting bytes
*   Use client hints
*   SVG's are smaller but they do not render always faster than other formats. Especially when they are very complex. Render speed is also included with the load time of content.

### CSS

*   Add inline critical CSS (see [Authoring Critical Above-the-Fold CSS](https://css-tricks.com/authoring-critical-fold-css/))
*   Remove unused CSS files
*   Remove unused selectors (see [unused-css](https://unused-css.com))
*   Reduce render-blocking stylesheets (such as with [`loadCSS`](https://github.com/filamentgroup/loadCSS))
*   Look out for [Paint and Layout triggering effects](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/)

### HTML

*   Remove inline styles

### JavaScript

*   Concatenate JavaScript files
*   Load JavaScript and CSS later so they don’t block rendering
*   Move script links in `<head>` to bottom of document
*   Add `defer` and `async` to all `<script>`s if they are not necessary to
    render above-the-fold content
*   Remove jQuery

### Fonts

*   Use something like `font-display: swap`

## Backend optimisation

*   If you’re using templates (such as in wordpress), make sure they don’t
    include things you aren’t using
