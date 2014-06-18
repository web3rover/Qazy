Qazy
====

Lazy Loading - No SEO Negative Impact

Qazy is a image lazy loader and is library agnostic (no jQuery).

Qazy removes the <a href="http://qnimate.com/lazy-loading-images-and-its-seo-impact/">negative SEO impact</a>. This is what makes it different from other lazy loaders.

Load the script as soon as possible in the webpage so that it can start tracking the images and load them lazily.

<a href="http://labs.qnimate.com/qazy-lazy-loading/">Live Preview</a>

This is a sample markup to make a image to be loaded lazily
<pre>
&lt;!-- data-qazy is set to true means to load it lazily. Set it to false if you don't want to load it lazily. --&gt;
&lt;!-- A default placeholder is used. To change the placeholder, assign the variable &quot;qazy_image&quot; with the placeholder image url before the script is loaded. --&gt;
&lt;img src=&quot;offline-web-apps.jpg&quot; data-qazy=&quot;true&quot;&gt;
</pre>

A complete working example code
<pre>
&lt;!doctype html&gt;
&lt;html&gt;
    &lt;head&gt;
        &lt;title&gt;Qazy&lt;/title&gt;
        &lt;script&gt; var qazy_image = &quot;http://qnimate.com/blank.gif&quot;;  &lt;/script&gt;
        &lt;script src=&quot;qazy.js&quot;&gt;&lt;/script&gt;
    &lt;/head&gt;
    &lt;body&gt;
        &lt;img src=&quot;lazy-loading.jpg&quot; data-qazy=&quot;true&quot;&gt;
        &lt;br&gt;
        &lt;img src=&quot;offline-web-apps.jpg&quot; data-qazy=&quot;true&quot;&gt;
        &lt;br&gt;
        &lt;img src=&quot;random-color.jpg&quot; data-qazy=&quot;true&quot;&gt;
        &lt;br&gt;
        &lt;img src=&quot;revel-scroll.jpg&quot; data-qazy=&quot;true&quot;&gt;
        &lt;br&gt;
        &lt;img src=&quot;wordpress-fields-metaboxes.jpg&quot; data-qazy=&quot;true&quot;&gt;
    &lt;/body&gt;
&lt;/html&gt;
</pre>
