HEADERS
===============================

# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

Heading Level 1
===

Heading Level 2
---

===============================



PARAGRAPHS
===============================

Paragraphs are designated by raw text.

Separate paragraphs are designated by one line of empty space between, like the previous line.

===============================



LINE BREAKS
===============================

To make a line break include two spaces after a line like so.__
The underlines there are for visualization purposes, since spaces are invisible. Don't include them normally.__
All of these lines would be part of the same paragraph tag with line break tags contained inside.

===============================



EMPHASIS
===============================

Bold text is indicated by **double asterisks** or __double underlines__.

Italicized text is indicated by *single asterisks* or _single underlines_.

Bold AND italicized text can be done using ***triple asterisks*** or ___triple underlines___.
This can also be done using __*this*__ and **_this_**

===============================



BLOCKQUOTES
===============================

> Blockquotes are indicated using this character at the start of a line.

> Blockquotes can include multiple paragraphs in the same block by adding the same character to separating empty lines as such.
>
> This would be another paragraph.
>
>> This would be a nested blockquote.

===============================



> ### Blockquotes can include certain other elements.
>
> - Such as this
> - The header starting this blockquote
>
> and *Emphasize* **text**

LISTS
===============================

1. ordered lists are created using line items with numbers followed by periods
1. the numbers don't have to be in numerical ordered, but should start with the number 1
2. the list elements can be nested
    1. such as this
    2. and this

- unordered lists simply require a series of line items starting with \-, \*, and \+
    - these lists can be nested
    - as well
- 20\. numbers with periods following them must have the period escaped to avoid ordered list confusion

- lists can be interjected with other elements as long as the elements are one tab or four spaces in
- this can be seen in the blockquote below
    > this blockquote is one tab in
- this blockquote wont affect the continuity of the list

1. you can nest different list types
    - like this
    - and this
2. and they will render correctly

===============================



CODE BLOCKS
===============================

to create code blocks
    <html>
        <head>
            <title>Make sure they are indented at least one tab or four spaces</title>
        </head>
    <html>

- to create code blocks in lists
        <html>
            <head>
                <title>Make sure they are indented an additional tab or an extra four spaces</title>
            </head>
        </html>
- the above will render correctly

===============================



IMAGES
===============================

images can be represented by
![Image Name](/path/to/image.png)

links can be added to images by enclosing the image in square brackets and adding the link in parentheses
[![Linked Image](/path/to/image.png)](https://clarkeriksson.com)

===============================



BACKTICKS
===============================

code can be designated by enclosing the word or phrase in `backticks`

``enclosing a word or phrase in double backticks escapes the `backticks` inside``

===============================



HORIZONTAL RULE
===============================

to create a horizontal rule use three or more asterisks, dashes, or underscores on a line as such
***
---
___

===============================



LINKS
===============================

links can be created using a similar syntax to [Images](https://clarkeriksson.com) except without the exclamation point.

titles can be added to links by following the [Link](https://clarkeriksson.com "With a word or phrase enclosed in quotation marks")

adding raw links to URL's or email addresses can be done using angle brackets such as in <erikssonclarkw@gmail.com> and <https://clarkeriksson.com>

emphasis may be added to links around the entire block such as in *[This](https://clarkeriksson.com)* and **[This](https://clarkeriksson.com)**
code style may be added to links inside the square brackets such as in [`This`](https://clarkeriksson.com)

===============================



REFERENCES
===============================

references comprise of two parts. the first part is the [link][1] where the first portion is the highlighted text and the second points to the label of the reference
this first part can have a space between the two portions like [so] [2]
the second part of the link is not case sensitive, and can include letters, numbers, spaces, and punctuation

the second part is the reference itself, which are formatted according to the following rules:
    1. The label, in brackets, followed immediately by a colon and at least one space
    2. The URL for the link, which can optionally be enclosed in angle brackets
    3. The (optional) title for the link, which can be enclosed in double quotes, single quotes, or parentheses
Examples:
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
    - [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
    - [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
    - [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
you can place these anywhere in the markdown document

===============================



HTML
===============================

HTML can be added simply into the markdown by placing the tags in your **markdown** <em>text</em>

you cannot use markdown syntax inside HTML tags

===============================



ESCAPING CHARACTERS
===============================

use a backslash to escape characters that would usually be used to format the text

* this is a bullet in an unordered list
\* this would just be text starting with an asterisk character

===============================