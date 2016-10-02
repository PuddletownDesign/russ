<<<<<<< HEAD
# Review time

> spark the wicks an', However I master the trick just like Nixon - Raekwon


## Things to look out for

Keep taking and organizing more notes. Gotta keep a solid reference for yourself through this. All of these readme files are lacking a little bit. Keep the markdown notepad open!

I've made each of these into a trello task. Check em off as you go along.

## Tasks

### 01-git

Well I've renamed all the branches... You gonna have to deal with that. Protip: you can just delete the old ones in this case. However you have to pull and rebranch them all.

https://github.com/PuddletownDesign/russ/blob/01-git/task2.md

### 02-vim

Just work on filling this in while you learn vim and get your snippets dialed in.

https://github.com/PuddletownDesign/russ/blob/02-vim/README.md

### 03-html-basic

https://github.com/PuddletownDesign/russ/blob/03-html-basic/task2.md

### 04-markdown

https://github.com/PuddletownDesign/russ/blob/04-markdown/task2.md

### 05-css-basic
=======
# Markdown

## What we use markdown for

Markdown is the modern way to write documentation and format text. It's used on github for all md files, some of it works in slack, you can leave reddit comments in it. It's pretty widely used.

It's used for writing html tags for content, not for site structure or any other kinds of tags. Just the main article content tags. It's designed to look similar to email style syntax.

## What it does

Markdown when processed turns into simple HTML. For example the two hash signs turn the above into an h2. three is an h3. Two new blank lines become p tags etc. There's a bunch of different markdown processors, they each have some differences. Slack's is very limited, Githubs is really extensive. Especially with code. make sure to choose the right language on github when adding code blocks.

## Tools 

* [dillinger.io](dillinger.io) - handy online markdown editor that lets you save directly to github
* [Plasticboy](https://github.com/plasticboy/vim-markdown) - Vim Markdown support

## Syntax

* [Paragraphs](#Paragraphs)
* [Italic, Bold, Bold Italic](#Italic)
* [Headers](#Headers)
* [Lists](#Lists)
* [Line Breaks](#breaks)
* [Links](#Links)
* [Images](#Images)
* [Block Quote](#quote)
* [HTML](#html)
* [Further Reading](#futher)

<a name="Paragraphs"></a>

### Paragraphs
Paragraphs are generated automatically by placing an empty line in between two sections of text.


<a name="Italic"></a>

### Italic, Bold & Bold Italic
To make bold, italic or bold italics, wrap the section of text in asterisks. 1 asterisk for italic, 2 for bold and 3 for both.

\*italic*    
\*\*bold**    
\*\*\*bold italic***    

<a name="Headers"></a>

### Headers
Headers are created by putting a pound sign in front of a line of text. This text must be on it's own line. The h1 or top level header on a page is the title. You will be defining the H2 - H6 headers. I have not added formatting for headers below h4. You will rarely need that much structure in a document. 

## \#\#header level 2   
### \#\#\#header level 3   
#### \#\#\#\#header level 4   
##### \#\#\#\#\#header level 5   
###### \#\#\#\#\#\#header level 6   
*Pardon the formatting, the headers are not set up to be used one after another*.
    
<a name="Lists"></a>

### Lists

#### Unordered Lists
Unordered lists are created by placing an asterisk and a space in front of a line of text.

\* item 1    
\* item 2    
\* item 3    

becomes...

* item 1
* item 2
* item 3


#### Ordered Lists
Ordered lists are created by placing an number, period and a space in front of a line of text. Order lists are used for *(you guessed it)* lists that go in a certain order. use unordered lists for everything else.

1. item 1    
2. item 2    
3. item 3   

<a name="breaks"></a>

### Line Breaks
Say you are trying to write a piece of poetry. Instead of making a paragraph which would space out the lines too much you could use a line break. line breaks are made by **placing four spaces at the end** of a line of text.

and you get this....

old pond    
a frog jumps    
the sound of water    

<a name="Links"></a>

### Links
To make a link put the text that the link will have inside of square brackets. Directly to the left add the link in parenthesis, do not put a space in between the parenthesis and the brackets.

this...    
I think that \[Stack Overflow](http://stackoverflow.com) is all that we have going for us.

turns into this...     
I think that [Stack Overflow](http://stackoverflow.com) is all that we have going for us.

You can also make non text links by adding less then and greater than signs around a url.

this    
< http://stackoverflow.com >    
(*don't place any spaces in between the url and < > marks, i just couldn't get it to format right*)

turns into this    
<http://stackoverflow.com>

<a name="Images"></a>

### Images

To Link an images in posts, is very similar to adding a text link, except you put an exclamation point in front of the brackets. The text that you add in the brackets is the image alt value. Give the image a descriptive label in the brackets. I  suggest you put images on their own lines. Otherwise the text might wrap around them. If you can set it up to look good wrapping, then go for it.

This    
!\[Ronald after midnight](http://i825.photobucket.com/albums/zz172/puddletown/ronald.jpg)

Turns into this    
![Ronald after midnight](http://i825.photobucket.com/albums/zz172/puddletown/ronald.jpg)

<a name="quote"></a>

### Block quote
If you are quoting somebody else in a block of text you can add a block quote by placing a greater than sign in front of a line of text

\> "Conversation about the weather is the last refuge of the unimaginative."      
-- Oscar Wilde 

Turns into this...    
> "Conversation about the weather is the last refuge of the unimaginative."    
-- Oscar Wilde 

<a name="html"></a>

### Blocks of code for display

#### Block of Javascript

\`\`\`javascript    
function test() {    
	this_is_a_fuction();    
}    
\`\`\`

Turns into this

```javascript
function test() {
	this_is_a_fuction();
}
```

### HTML
You can insert bits of HTML directly into the text boxes where ever you want them. Make sure you leave a line of white space above and below the HTML. **Do not put any javascript into the boxes.** HTML will only work for you in the text boxes. Comments text boxes accept markdown but do not render HTML.

<a name="futher"></a>

## Further Reading
For further reading on everything markdown can do (and it can do a lot more), check out the [Daring Fireball Guide to markdown](http://daringfireball.net/projects/markdown/syntax). That will fill you in on advanced features and it's limitations.

// again, your notes are much better than mine, but i'm completing the assignment \\

## Markdown:
	* this document is formatted using Markdown
	* consists of quick replacements for certain html tags
		* > here is a blockquote
		* >- here is the citation
		* *anotates italics*
			** subgroups
			** _underscores_ also delcare italics/bold/bold-italics in the same way that * does
		* **declares bold**
		* ***declares bold/italics***
		* ~~strikethrough.~~ done with "~~"
	1. this is a numbered list item
	2. this is also a numbered list item
	4. < doesn't matter which number you use, as long as you use a number; however, use the correct one to kep code clean and legible.
		* can have unordered sublists like this
			** which also can have their own sublists like this		1. and numbered sublists				2. as well

	* paragraphs can exist within list items
		line breaks can be done with two spaces  		and still remain in the same paragraph  
	* unordered lists can use asterisks, minuses, and pluses
	* two ways to create links:
		* [inline-style link](https://www.google.com)
		* [inline-style w/ title](https://www.google.com "Google's Homepage")
		* [reference-style link][Arbritrary case-insensitive reference text]
		* [relative reference to a repository file](../blob/master/LICENSE)
		* [can use numbers for reference-style link definitions][1]
			** or leave it empty and use the [link text itself]
		* URLs and URLs in angle brackets will automatically get turned into links.  
			** http://www.example.com or <http://www.example.com> and sometimes example.com(just not on GitHub)  		
			** some text to show that the reference links can follow later.
				+++ [arbitrary case-insensitive reference text]: https://www.mozilla.org  
				[1]: http://slashdot.org  
				[link text itself]: http://www.reddit.com
	### Code and syntax highlighting:
		* inline `code` has `back-ticks` around it
		* blocks of code are fenced with three back-ticks ``` or identifed w/ 4 spaces (use back-ticks)
		* raw HTML can be used inside of markdown most of the time 
		* Markdown does not work very well in HTML, so use HTML tags 
	### Horizontal Rule and line breaks:
		* three or more hyphens, asterisks, or underscores
		* line breaks are done with double returns

		like so

		and single returns
		like so
>>>>>>> 7aade64a850469415d13b3749e1cd56519176c6a

https://github.com/PuddletownDesign/russ/blob/05-css-basic/task2/task2.md