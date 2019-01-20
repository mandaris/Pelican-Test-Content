title: Table of Contents   
date: 2018-07-27 22:17:50  
category: blogging  
tags: misc  
status: published 

[TOC]

This is the  whether a table of contents will look good in my theme.

In order to add this you have to have something similiar to the following in your `pelicanconfig.py`.

```python
# Markdown Plugins
MARKDOWN = {
    'extension_configs': {
        'markdown.extensions.codehilite': {'css_class': 'highlight'},
        'markdown.extensions.extra': {},
        'markdown.extensions.meta': {},
        'markdown.extensions.toc': {'baselevel': '3', 'title': 'Table of Contents'},
        'figureAltCaption':{},
    },
    'output_format': 'html5',
}
```
Please see the [Pelican Documentation on Markdown Settings](http://docs.getpelican.com/en/stable/settings.html)

# First main header
Some random Text. 
## Sub Heading One
Fine points to be made. [Link to nothing][].

Other stuff goes here. Also, I love my wife.

## Sub Heading Two
Some more text that I've spent some time coming up with. Also, I want to spend some time looking into the things!

# Second Main Header
Another point.
## Mini-Header
Some text.
### Finer point on the issue
I can't go that far
### So fine you blew my mind
I don't know what else to add
##  Another header that showed up

# Conclusion
Definitely not how I currently write, but I want to add it for others.