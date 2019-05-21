title: Theme Tour  
date: 2018-07-31 08:18:06  
category: blogging  
tags: test, tour  
status: published    

![Example of a large image.](images/example-large-image.png "Just another example image.")

[TOC]

# Goal for this document
I wanted to make a page that contained most if not all of the different things that you would find in a blog post written in Markdown. For simplicity, I'll stick to what is found in [Python-Markdown][pm] as it is the one that I use most.

[pm]: https://python-markdown.github.io/ "A Python implementation of John Gruber's Markdown."

# Basic Syntax

This sentence as *emphasied* and **bold** text.

This is a sentence with a [link][].


# List
There are two kinds of lists.

## Unordered lists

+ First item
+ Second item. This second item has two paragraphs in it.

    This is the second line of the second item. Not confusing at all.
	
+ Third item

## Ordered lists

1. First item
2. Second item
3. Third item

A small paragraphe between the a second list.

4. Forth item - If this doesn't start with 4 than smart list are not on.
5. Fifth item
6. Six item

# Footnotes
I am going to use the example from the footnote [documentation](https://python-markdown.github.io/extensions/footnotes/ "The Footnotes extension adds syntax for defining footnotes in Markdown documents.")[^footnote].

[^footnote]:
    The first paragraph of the definition.

    Paragraph two of the definition.

    > A blockquote with
    > multiple lines.

        a code block

    A final paragraph.

# Block quote
Something simple should go here.

> Remember, you have within you the strength, the patience, and the passion to reach for the stars to change the world.
> - Harriet Tubman

# Tables
This is my tables section. These were taken from https://markdown-it.github.io/

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

# Misc
This is the things that most people don't really use.

## Definitions

Apple
:   Pomaceous fruit of plants of the genus Malus in 
    the family Rosaceae.
:   An American computer company.

Banana
:   a tropical plant of the genus _Musa_

Orange
:   The fruit of an evergreen tree of the genus Citrus.

## Code blocks

```python hl_lines="1 3"
# This line is emphasized
# This line isn't
# This line is emphasized
```

## Abbreviations
The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language

*[W3C]:  World Wide Web Consortium

## Attribute List
This is a [link](http://example.com){: class="foo bar" title="Some title!" }.