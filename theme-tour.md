title: Theme Tour  
date: 2028-07-31 08:18:06  
modified: 2019-07-19 17:36:53  
category: blogging  
tags: test, tour  
status: published    

![Example of a large image. Puppy running to camera.](/images/joe-caione-781415-unsplash.jpg "Photo by Joe Caione on Unsplash.")

[TOC]

# Goal for this document
I wanted to make a page that contained most if not all of the different things that you would find in a blog post written in Markdown. For simplicity, I'll stick to what is found in [Python-Markdown][pm] as it is the one that I use most.

[pm]: https://python-markdown.github.io/ "A Python implementation of John Gruber's Markdown."

# Basic Syntax

This sentence as *emphasied* and **bold** text.

This sentence has `code` written in it.

This is a sentence with a [link](https://duckduckgo.com "The search engine that doesn't track you. ").

## Multiple Paragraphs of text
Pack my box with five dozen liquor jugs. Several fabulous dixieland jazz groups played with quick tempo. Back in my quaint garden, jaunty zinnias vie with flaunting phlox[^reference]. Five or six big jet planes zoomed quickly by the new tower. Exploring the zoo, we saw every kangaroo jump and quite a few carried babies. I _quickly_ explained that many big jobs involve few hazards. Jay Wolf is quite an expert on the bass violin, guitar, dulcimer, ukulele and zither. Expect skilled signwriters to use many jazzy, quaint old alphabets effectively. The wizard quickly jinxed the gnomes before they vaporized. THE QUICK BROWN FOX JUMPED OVER THE LAZY DOG'S BACK 1234567890[^alternatives].

[^reference]: A footnote in the middle of a larger paragraph has a footnote somewhere else.

[^alternatives]: These were all alternatives to the [famous pangram](https://en.wikipedia.org/wiki/The_quick_brown_fox_jumps_over_the_lazy_dog "From Wikipedia, the free encyclopedia") for testing fonts found [here](https://wookiecode.blogspot.com/2012/05/handwriting-aids-and-links-to-lesson.html "Alternatives to: The quick brown fox jumps over the lazy dog."). 

*Lorem ipsum dolor sit amet*, eu detracto senserit vis, ei `natum` ridens detracto sit. Id iriure prompta vix. _Sit ea feugiat invenire similique_, etiam solet eleifend cu per. **Ea falli nullam elaboraret vis**, modo percipitur omittantur at ius, _in quo nullam timeam ocurreret_. Est ad deleniti corrumpit scripserit, te usu **apeirian recusabo oportere**, nemore laboramus vulputate te vim. Ea eum mazim iudicabit, `harum utroque` pri ne.

Per no putant iriure [intellegebat](#). Tamquam maiorum ei eum, ea iuvaret maluisset liberavisse eam, adhuc falli _tamquam ius te?_ Eu amet virtute scaevola est, simul **nusquam** invidunt duo id, at usu sanctus abhorreant definiebas! Vide ullum quo cu? Ius in forensibus sadipscing, dicant aperiri volutpat et sit.

Veri dicat pro te, an aliquam reprimique cum, et pro commune maiestatis. Nec ex amet [eleifend definitiones](#)! An adipisci `consequuntur` est. In quot oratio vis. Vide nobis aperiam pri ad, et sit dictas adolescens inciderint, pertinacia referrentur consequuntur pri id?


# List
There are two kinds of lists.

## Unordered lists

+ First item.

+ Second item. This second item has two paragraphs in it.

    This is the second line of the second item. (Not confusing at all.)
	
+ Third item.

## Ordered lists

1. First item
2. Second item
3. Third item

A small paragraph before the second list.

4. Forth item - If this doesn't start with 4 than smart list are not on.
5. Fifth item
6. Six item

# Footnotes
I am going to use the example from the footnote [documentation](https://python-markdown.github.io/extensions/footnotes/ "The Footnotes extension adds syntax for defining footnotes in Markdown documents.")[^footnote]. 

[^footnote]: The first paragraph of the footnote.

    The second paragraph of the footnote.

    > A blockquote with
    > multiple lines.

        a code block

    A final paragraph in the same foot note.

# Block quote
Something simple should go here.

> Remember, you have within you the strength, the patience, and the passion to reach for the stars to change the world.
> - Harriet Tubman

Sometimes you might have nested block quotes.

> > You miss 100% of the shots you don't take.
> > - Wayne Gretzky
>
> Michael Scott

# Tables
This is my tables section. These were taken from https://markdown-it.github.io/ and https://michelf.ca/projects/php-markdown/extra/#table.

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

## Right aligned columns

| Option | Description                                                               |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

## Centered values

| Item      | Value |
| :-------: | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |


| Function name | Description                      |
| ------------- | -------------------------------- |
| `help()`      | Display the _help_ window.       |
| `destroy()`   | **Destroy your computer!**       |

# Misc
These are the things that most people don't really use.

## Definitions

Apple
:   Pomaceous fruit of plants of the genus Malus in the family _Rosaceae_.
:   An American computer company.

Banana
:   A tropical plant of the genus _Musa_.

Orange

Pinapple
:

Mango


### Complex definitions 

Term 1

:   This is a definition with two paragraphs. Lorem ipsum 
    dolor sit amet, consectetuer adipiscing elit. Aliquam 
    hendrerit mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus.

:   Second definition for term 1, also wrapped in a paragraph
    because of the blank line preceding it.

Term 2

:   This definition has a code block, a blockquote and a list.

        code block.

    > block quote
    > on two lines.

    1.  first list item
    2.  second list item

## Code blocks

```python hl_lines="2 4 9"
import logging
# This line is emphasized
# This line isn't
# This line is emphasized

def func():
    # function body
    someValue = "func called"
    logging.info(someValue)

if __name__ == '__main__':
    func()

```

## Abbreviations
The HTML specification is maintained by the W3C. This example taken from https://python-markdown.github.io/extensions/abbreviations/

*[HTML]: Hyper Text Markup Language

*[W3C]:  World Wide Web Consortium

## Attribute List
This is a [link](http://example.com){: class="foo bar" title="Some title!" }.
