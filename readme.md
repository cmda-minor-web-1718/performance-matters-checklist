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
* The following CSS files are all blocking, while almost none are needed for the home-page. A better option would be to load these with async, so they wont block the page load. For the needed css in styles.css you can add this inline in the html, to leverage the power of critical css. https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery 
*  <link rel='stylesheet' id='contact-form-7-css'  href='https://www.cmd-amsterdam.nl/wp-content/plugins/contact-form-7/includes/css/styles.css?ver=4.7' type='text/css' media='all' />
<link rel='stylesheet' id='woocommerce-layout-css'  href='//www.cmd-amsterdam.nl/wp-content/plugins/woocommerce/assets/css/woocommerce-layout.css?ver=3.0.4' type='text/css' media='all' />
<link rel='stylesheet' id='woocommerce-smallscreen-css'  href='//www.cmd-amsterdam.nl/wp-content/plugins/woocommerce/assets/css/woocommerce-smallscreen.css?ver=3.0.4' type='text/css' media='only screen and (max-width: 768px)' />
<link rel='stylesheet' id='woocommerce-general-css'  href='//www.cmd-amsterdam.nl/wp-content/plugins/woocommerce/assets/css/woocommerce.css?ver=3.0.4' type='text/css' media='all' />
<link rel='stylesheet' id='rgs-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/css/rgs.css?ver=6.0.1' type='text/css' media='all' />
<link rel='stylesheet' id='font-awesome-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/css/font-awesome.min.css?ver=4.6.10' type='text/css' media='all' />
<link rel='stylesheet' id='main-styles-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/style.css?ver=7.5' type='text/css' media='all' />
<link rel='stylesheet' id='pretty_photo-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/css/prettyPhoto.css?ver=7.0.1' type='text/css' media='all' />
<!--[if lt IE 9]>
<link rel='stylesheet' id='nectar-ie8-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/css/ie8.css?ver=4.6.10' type='text/css' media='all' />
<![endif]-->
<link rel='stylesheet' id='responsive-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/css/responsive.css?ver=7.5' type='text/css' media='all' />
<link rel='stylesheet' id='options_typography_OpenSans_ext-css'  href='https://fonts.googleapis.com/css?family=Open+Sans%3A300%2C400%2C600%2C700&#038;subset=latin%2Clatin-ext' type='text/css' media='all' />
<link rel='stylesheet' id='woocommerce-css'  href='https://www.cmd-amsterdam.nl/wp-content/themes/salient-7.5.02-good/css/woocommerce.css?ver=7.5' type='text/css' media='all' />
<!-- This site uses the Google Analytics by MonsterInsights plugin v6.1.7 - Using Analytics tracking - https://www.monsterinsights.com/ -->
<script type="text/javascript" data-cfasync="false">


### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Backend optimisation

*   Add some more points here...
