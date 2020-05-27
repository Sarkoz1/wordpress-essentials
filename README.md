# Wordpress and Woocommerce Essentials

This repo includes the most usable functions and pieces of code of Wordpress and Woocommerce

## Table of Contents: Wordpress

- Posts
- Shortcodes
- Contact Form 7

## Table of Contents: Woocommerce
- [FlexSlider](#flexslider)
- Variations

## FlexSlider
To manipulate woocommerce image slider in product page you can add the following code to your .js file:
```javascript
var gallerySlider = $('.woocommerce-product-gallery').data('flexslider');
    /* You can manipulate slider below */
    gallerySlider.flexslider('next'); // Goe to next slide
```
Full list of FlexSlider events:
https://github.com/woocommerce/FlexSlider#general-notes

