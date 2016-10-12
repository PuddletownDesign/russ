# SASS/SCSS

Ok so now you've gotten pretty good with writing out vanilla CSS, time to make CSS a lot more fun.

SASS/SCSS are superset languages that compile down to CSS. They have all these cool features like compiling multiple style sheets into one and nesting selectors.

**For the record, I use SCSS**, not SASS for one simple reason, normal CSS is valid SCSS, however it is not that case with SASS. SASS has it's own style of styntax. You read up and decide what to do, but let's just start with SCSS.

## Read up on it here:

http://sass-lang.com/guide

## Task one

1. Set up scout first off. It's an Adobe Air app. We will be using this to compile SCSS just in the short term. We will have better non-GUI tools for this later. I still use this app a lot for quick and dirty edits. http://scout-app.io/
2. Set up the project. You want to read from the `scss` directory and output into the `css` directory. You will never need to open the `styles.css` file.
3. Rebuild the last task but with SCSS this time. Make sure to always set output to `production`/ `compressed`. something like this. 

![SCSS config example](http://tinyimg.io/i/CMjBPQo.png)

## What's going on here?!?!

The first file that Scout will load will be the `scss/styles.scss` file. In this file we're including several others in a specific order. This file will be compiled into `css/styles.css`.

1. `includes/_colors.scss` is loaded next. it has some basic color information. It's cool to put these one place so you only need to change one value if a client requests a change.
2. Then the reset is loaded.
3. Followed by the typography framework
4. Finally `_layout.scss` is called this is where we will be working.

You'll only be working with the `_layout.scss` in this chamber.

##Specs

We're just going to rebuild the same layout as in 07-css-advanced task3 but with SCSS.

1. Define your colors in the color file and assign the variable to each property. I usually stick with general color names or slgiht variations. (ex. blue, l-blue, d-blue, black, grey). That way if a client wants the dark blue darker it will be one line to change `d-blue`. Rarely will you need to define colors more specifically.
2. Nest your selectors
3. Use the `lighten()` function for the `#form form` background color instead of defining a specific color.


## Helpful links

* [Scout app](http://scout-app.io/)
* [SCSS Documentation](http://sass-lang.com/guide)