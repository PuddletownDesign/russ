# CSS Basic

> For the love of god add documentation. Keep that damn markdown window open and write everything down. -RZA

CSS is the styling language used to apply to HTML. You select HTML elements and apply styles to them.

## What CSS is and how it works

## Selectors

* tag		- ex. `body p`
* id		- ex. `#message p`
* class		- ex. `.message p`

## Attributes

* `margin` -  adds space around the outside of the box
* `padding` - adds space to the inside of the box
* `background-color` - changes the background color of the element
* `width` - sets the width of the element
* `text-align` - left, center, right
* `color` - color of the text in an element

// my notes\\\

## syntax:
	* example:
		** tag Selectors:
			selector {
					property: value;
					}
		** id Selectors:
			#selector {
					property: value;
					}
			*** can only be used once per page
				**** on that tip, it's considered good practice to pick your selectors wisely
		** class selectors:
			.selector {
					property: value;
					}

## stylesheet insertion:
	* external stylesheet:
		** <link rel="stylesheet" type="text.css" href="style.css" />
	* internal style:
		** <style type="text/css>selector {property: value;}</style>
	* inline style:
		** <tag style="property: value">

