Qazy
====

Lazy Loading - No SEO Negative Impact

Qazy is a image lazy loader and is library agnostic (no jQuery).

Qazy removes the <a href="http://qnimate.com/lazy-loading-images-and-its-seo-impact/">negative SEO impact</a> that is caused by other lazy loaders.

Load the script as soon as possible in the webpage so that it can start tracking the images and load them lazily.

<a href="http://labs.qnimate.com/qazy-lazy-loading/">Live Preview</a>

This is a sample markup to make a image to be loaded lazily
<code>
<!-- data-qazy is set to true means to load it lazily. Set it to false if you don't want to load it lazily. -->
<!-- A default placeholder is used. To change the placeholder, assign the variable "qazy_image" with the placeholder image url before the script is loaded. -->
<img src="offline-web-apps.jpg" data-qazy="true">
</code>

A complete working example code
<code>

<!doctype html>
<html>
    <head>
        <title>Qazy</title>
        <script> var qazy_image = "http://qnimate.com/blank.gif";  </script>
        <script src="qazy.js"></script>
    </head>
    <body>
        <img src="lazy-loading.jpg" data-qazy="true">
        <br>
        <img src="offline-web-apps.jpg" data-qazy="true">
        <br>
        <img src="random-color.jpg" data-qazy="true">
        <br>
        <img src="revel-scroll.jpg" data-qazy="true">
        <br>
        <img src="wordpress-fields-metaboxes.jpg" data-qazy="true">
    </body>
</html>
</code>
