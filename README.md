mg
==============

A minimal theme with a green header bar for [Pelican](http://blog.getpelican.com/).

Warning
--------------
mg is still under development and may do anything it likes up, don't use it on
a production site! 
You have been warned!

Live Example
--------------
Check out [my blog](http://www.devsbytes.com).

Features
--------------

* [Open Graph](http://ogp.me/) supports for pages and articles.
* Comment with DISQUS.
* Google Analytics.
* Responsive design.
* Share buttons built with share urls.
* Meta tags for description, author and copyright.
* Custom footer notice.

Anti-Features
--------------

* Support only a single author blog
* Support only ATOM feeds
* Currently blogroll is disabled
* Tag and tags pages style needs to be improved.

Settings
--------------

All settings are optional.

**ALT_NAME**  
An alternative name for your site. It appears in the header bar.

**DESCRIPTION**  
A brief description of your site, for Open Graph and search engines.

**FOOTER**  
A custom footer notice.

**OG_IMAGE**  
The path of a custom image for the `og:image` meta property.
The path is relative to the "/static/" folder of your site, so if your image
is placed at "www.example.com/static/img/pic.png", the path to insert is "img/pic.png"

**OG_IMAGE_TYPE**  
The MIME type for **OG_IMAGE**.

**OG_IMAGE_WIDTH**  
The width of **OG_IMAGE**. 

**OG_IMAGE_HEIGHT**  
The heigth of **OG_IMAGE**.

**SHARE**  
Enable share buttons, boolean.

**SOCIAL**  
A list of tutples (icon, URL). The icons are from [Font Awesome]
(http://fortawesome.github.io/Font-Awesome/). The suffix "-square" is removed 
in the footer icons of the small screen layout.  
e.g.  
```python
    SOCIAL = (('twitter', 'https://twitter.com/luca_chr'),
              ('google-plus-square', 'https://plus.google.com/117284397605208270870'),
              ('github', 'https://github.com/lucachr'),
              ('envelope', 'mailto:luca92web@gmail.com'),)
```
