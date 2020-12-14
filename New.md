# Markdown
![alt text](https://miro.medium.com/max/2800/0*V9tvdEAZmSjBG3Ny.gif)

Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

## What is Markdown?

Markdown is a way to style text on the web. 

### You can use Markdown most places around GitHub:

1. Gists
2. Comments in Issues and Pull Requests
3. Files with the .md or .markdown extension

## Examples

1. Text:
 
It's very easy to make some words **bold** and other words *italic* 

`with Markdown. You can even [link to Google!](http://google.com)`

The output
with Markdown. You can even [link to Google!](http://google.com)
2. Lists:

Sometimes you want numbered lists:

`1. One
2. Two
3. Three`

The output
1. One
2. Two
3. Three

Sometimes you want bullet points:

`* Start a line with a star
* Profit!`

The output
* Start a line with a star
* Profit!

Alternatively,

`- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this`

Output
- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

** It is important to solve Challenges using the growth mindset; you have to try another way for solving when your way is not working **

2. Obstacles:

My first impulse when I hit a roadblock is to immediately divert my attention to something else. I lose focus, just like it says in the chart above. Whether it’s clicking a tempting bookmark in my browser, nipping out to grab a coffee, or just about anything to delay keeping at it and fighting through the discomfort. A coworker calls this “instant gratification monkey syndrome.” It’s the idea that we’ll do just about anything other than the actual task at hand if it has suddenly become challenging, and especially when there are so many tempting diversions – articles, videos, email, social – mere clicks away.

3. Imges:

If you want to embed images, this is how you do it:

`![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)`

The Output
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png

4. Headers & Quotes:

`# Structured documents`

The Output
# Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

### This is a third-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

You have learned to ask your self two questions:

1. What was the best part of the day?
2. What went wrong, and how can I make sure it doesn’t happen again?
These questions help you focus on all aspects of your day, the good and the bad, and they help you internalize strategies for creating more good days going forward.

5. Codes:

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks:``var example = true``.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

````
if (isAwesome){
  return true
}
````

the output:
```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```
5.  Extras

GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

# Syntax guide:

## Headers:

`# This is an <h1> tag

## This is an <h2> tag

###### This is an <h6> tag`

## Emphasis:

`*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_`

## Lists:

1. Unordered
 
`* Item 1
* Item 2
  * Item 2a
  * Item 2b`
  
 2. Ordered
 
`1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b`
  
## Images:

`![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)`

## Links:

`http://github.com - automatic!
[GitHub](http://github.com)`

## Blockquotes:

`As Kanye West said:

> We're living the future so
> the present is our past.`

## Inline code:

`I think you should use an
`<addr>` element here instead.`

# GitHub Flavored Markdown

GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

# Syntax highlighting
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

` ```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
``` `
You can also simply indent your code by four spaces:
`
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
`
Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True
## Task Lists:
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

# Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
