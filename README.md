# Github Markdown Cheat Sheet
#### This is a simple Github Markdown Cheat Sheet aiming to help me (and others) finding most used Markdown syntax for my projects.

- [Headings](#headings)
- [Styling text](#styling-text)
- [Quoting](#quoting)
- [Links](#links)
- [Lists](#lists)
- [Task lists](#task-lists)
- [Mentioning people and teams](#mentioning-people-and-teams)
- [Referencing issues and pull requests](#referencing-issues-and-pull-requests)



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

> Bold: **Bold**

> Italic: *Italic*

> Strikethrough: ~~Strikethrough~~

> Bold and nested italic: **Bold and _nested italic_**

> All bold and italic: ***All bold and italic***


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

`[Example of a linked file](linked-file.txt)`

> [Example of a linked file](linked-file.txt)

> GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. You can use all relative link operands, such as `./` and `../`.


## Lists
###### You can make an unordered list by preceding one or more lines of text with `-` or `*`.


#### Unordered lists
```
- George Washington
- John Adams
- Thomas Jefferson
```
- George Washington
- John Adams
- Thomas Jefferson


#### To order your list, precede each line with a number.
```
1. James Madison
2. James Monroe
3. John Quincy Adams
```
1. James Madison
2. James Monroe
3. John Quincy Adams


#### Nested Lists
###### You can create a nested list by indenting one or more list items below another item.
```
1. First list item
   - First nested list item
     - Second nested list item
```
1. First list item
   - First nested list item
     - Second nested list item


#### Task lists
###### To create a task list, preface list items with a regular space character followed by `[ ]`. To mark a task as complete, use `[x]`.
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

> If a task list item description begins with a parenthesis, you'll need to escape it with '\\':

- [ ] \(Optional) Open a followup issue

## Mentioning people and teams

> You can mention a person or team on GitHub by typing @ plus their username or team name. This will trigger a notification and bring their attention to the conversation. People will also receive a notification if you edit a comment to mention their username or team name. 

###### For more information about notifications, see "[About notifications](https://help.github.com/en/github/managing-subscriptions-and-notifications-on-github/about-notifications)".


## Referencing issues and pull requests

> You can bring up a list of suggested issues and pull requests within the repository by typing #. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

###### For more information, see "[Autolinked references and URLs](https://help.github.com/en/articles/autolinked-references-and-urls)".

