===
# The Local - Site Guide

### Tools 
+ Grunt / Grunt-SASS
+ Node-SASS / Libsass
+ Bower 
+ Edge (although you can use regular CSS transforms w/ an Iframe for "masking")

> Site is split up into a few categories:
> News - iFrame TV - Drinks - Food - Location

### SASS/SCSS breakdown
+ **[ app.scss ]:** - used to import all partials
+ **[ _reset.scss ]:** - resets styles and sets box sizing
+ **[ _variables.scss ]:** - defines variables, (does not directly produce css)
+ **[ _mixins.scss ]:** - site only uses mixins for media queries (does not directly produce css)
+ **[ _layout.scss ]:** - image helper classes, layout helper classes, sets original container 
+ **[ _type.scss ]:** - site serves modern enough of a market to use viewport widths (+media queries) for text scaling (has px fallback)
+ **[ _components ]:** - on larger sites this would typically be split up into various partials but being a small one page site I decided to keep it all here. With code folding it's easy enough to get to the right element.

### What's Next
Had to get the site up ASAP so went with the basics first, will be adding more interactive elements as time allows:
+ Turn location into animated SVG
+ Hover effects for images
+ Start setting up SEO / Google Analytics




 