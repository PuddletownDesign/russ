#Basic HTML 

HTML is a Markup language used to add semantic structure to a document. You want to pick the correct tags for each set of data.

## Best Practices

* Don't nest divs (it's sloppy)
* Stay away from divs and spans when you have a better option (it's lazy not to)
* Use the least amount of mark up you need

## Helpful Links

* http://html5doctor.com/element-index/
* [W3C HTML Validator](https://validator.w3.org/)  - All pages should be validated to ensure their integrity.



## Tag Reference

### Document structure

* `<!DOCTYPE>`	Specifies the document type
* `<html>`	Specifies an html document
* `<head`>	Specifies information about the document
* `<title>`	Specifies the document title
* `<meta>`	Specifies meta information
* `<script>`	Specifies a script
* `<style>`	Specifies a style definition
* `<link>`	Specifies a resource reference
* `<body>`	Specifies the body element
* `<article>`	Specifies an independent piece of content of a document, such as a blog entry or newspaper article
* `<section>`	Represents a generic document or application section.
* `<main>` Represents main area of the page
* `<aside>`	Specifies a piece of content that is only slightly related to the rest of the page.
* `<footer>`	Specifies a footer for a section and can contain information about the author, copyright information, et cetera.
* `<nav>`	Specifies a section of the document intended for navigation.

### Header elements

* `<h1> to <h6>`	Specifies header 1 to header 6
* `<header>`	Specifies a group of introductory or navigational aids.

### Block content elements

* `<p>`	Specifies a paragraph
* `<ol>`	Specifies an ordered list
* `<ul>`	Specifies an unordered list
* `<li>`	Specifies a list item
* `<blockquote>`	Specifies a long quotation
* `<code>`	Specifies computer code text
* `<pre>`	Specifies preformatted text


### Inline content elements

* `<a>`	Specifies an anchor (link)
* `<abbr>`	Specifies an abbreviation
* `<del>`	Specifies deleted text
* `<cite>`	Specifies a citation
* `<img>`	Specifies an image
* `<time>`	Specifies a date and/or time.
* `<em>`	Specifies emphasized text 
* `<strong>`	Specifies strong text
* `<sub>`	Specifies subscripted text
* `<sup>`	Specifies superscripted text
* `<q>`	Specifies a short quotation


### Non Semantic elements

* `<hr>`	Specifies a horizontal rule
* `<br>`	Inserts a single line break
* `<div>`	Generic Block element
* `<span>`	Generic inline element


### Tables

* `<table>`	Specifies a table
* `<tbody>`	Specifies a table body
* `<td>`	Specifies a table cell
* `<tfoot>`	Specifies a table footer
* `<th>`	Specifies a table header
* `<thead>`	Specifies a table header
* `<tr>`	Specifies a table row

### Forms
* `<form>`	Specifies a form 
* `<input>`	Specifies an input field
* `<textarea>`	Specifies a text area
* `<label>`	Specifies a label for a form control
* `<select>`	Specifies a selectable list
* `<option>`	Specifies an option in a drop-down list
* `<optgroup>`	Specifies an option group
* `<button>`	Specifies a push button


// your notes are actually way better than mine, i just added mine as per the assignment. \\

## Basic HTML:

### best practices
	* wrap document in ```<html><body></body></html>```
	* all pages have headers; ```<h1-h?>```, ```<h1>``` is main header, should be only 1 per page.
	* some tags must be nested inside other tags (i.e. ```<cite>``` must be inside ```<blockquotes>```)
	* ```<ol>``` is for ordered lists, ```<ul>``` is for unordered lists (think numbers vs. bullet points)
	* ```<li>``` works as list elements for both ```<ol>``` and ```<ul>```
	* every list needs to have a header
	* all tags should be lowercase
	* don't wrap lists w/ headers; headers should be above list
	* wrap paragraphs of text with the ```<p></p>``` tag
	* ```<p>``` for paragraph inside ```<blockquote> <cite>``` inside ```<blockquote>```
		** indent nested block level tag
### more basics:
	* things like ```<html>``` , ```<body>``` are called "elements"
	* plain text docs saved with ```.html``` extension
	* required structure: ```<!DOCTYPE html>, <html>, <head>, <body>```
		** ```<!DOCTYPE html>``` informs browser html version being used; this is the ```latest version``` command
			*** html5 can still be updated, so delcaring the version isn't necessary as most things will understand the most recent iteration of html5
		** ```<html>``` signifies the beginning of document
		** ```<head>``` signifies not visible; the top of the doc, including metadata, doc title (displayed in title bar of browser), links to external files
		** ```<body>``` signifies all visible content within the page  
		** attributes	
			*** basic syntax = ```<"element" href="https://afuckingwebsite.com/">"text link"</"element">``` (no quotes)
			*** types:
				**** id = identifies element 
				**** class = classifies an element
				**** src = specifies embeddable content
				**** href = provides hyperlink reference to a linked source

	* keep code organized and legible by indenting nested tags

