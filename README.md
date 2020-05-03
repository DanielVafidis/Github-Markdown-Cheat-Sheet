# Github Markdown Cheat Sheet
#### This is a simple Github Markdown Cheat Sheet aiming to help me (and others) finding most used Markdown syntax for my projects.


## Headings
###### To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading.

```
# Largest Heading (h1)
## Second largest Heading (h2)
### Third Heading (h3)
#### Fourth Heading (h4)
##### Second smallest heading (h5)
###### Smallest Heading (h6)
```


## Styling text
###### You can indicate emphasis with bold, italic, or strikethrough text.

```
Bold: ** ** or __ __ (cmd/ctrl + B)
Italic: * * or _ _ (cmd/ctrl + I) 
Strikethrough: ~~ ~~
Bold and nested italic: ** ** and _ _
All bold and italic: *** ***
```

### Examples:

Bold: **Bold**

Italic: *Italic*

Strikethrough: ~~Strikethrough~~

Bold and nested italic: **Bold and _nested italic_**

All bold and italic: ***All bold and italic***


## Quoting
###### You can quote text with a \> or call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.

```
> Quote this line

Call out `this part` of a sentence
```


## Links
###### You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut command + k to create a link.

```
[This is the text that will link](to this URL)
```

> Tip: GitHub automatically creates links when valid URLs are written in a comment. For more information, see "[Autolinked references and URLS.](https://help.github.com/en/articles/autolinked-references-and-urls)"

> You can link directly to a section in a rendered file by hovering over the section heading to expose the link

> You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

> [Example of a linked file](linked-file.txt)

GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. You can use all relative link operands, such as `./` and `../`.