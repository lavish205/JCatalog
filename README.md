JCatalog
========

A catalog for the Jamia's hostelers created by the hostelers themselves.

How the site was made?

Well, majority of the work was done by the Jekyll. It provided us with the basic site structure. The designing was totally on us.

The maps on each page was accomplished using [Google Static Maps API V2](https://developers.google.com/maps/documentation/staticmaps/index). This is an amazing API provided freely (at the time of writing this readme). The whole image is being generated by the above API, by using the parameters provided by us and after generation is gives us back that image. To have fun with the API go check out the above link.

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```html
<html>
  <head></head>
  <body>
    <h1>Here is heading</h1>
    <p>This is paragraph</p>
    <a href="#">highlighting with some arguments>
    <div>
      <h2>block 1</h2>
      <article>sometext</article>
    </div>
  </body>
</html>
```
