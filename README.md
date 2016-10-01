# HTML Basic

## More on git and corrections from 2-basic-html branch

First look over the changes I made to the 2-basic-html branch index.html file you pushed. We are recreating that same file formatting but with markdown.

https://github.com/PuddletownDesign/russ/blob/2-basic-html/index.html

You can compare the changes here:

https://github.com/PuddletownDesign/russ/commit/e898bb362fd5694709f9cfa182f7f8b5de35eedf

There's a comment at the bottom with a basic list of corrections. This'll take just a second but suddenly click and be very simple.

This is import to be able to compare changes in lines of code between commits. This is the intro to code comparison.

## What we use markdown for

Markdown is the modern way to write documentation and format text. It's used on github for all md files, some of it works in slack, you can leave reddit comments in it. It's pretty widely used.

It's used for writing html tags for content, not for site structure or any other kinds of tags. Just the main article content tags. It's designed to look similar to email style syntax.

## What it does

Markdown when processed turns into simple HTML. For example the two hash signs turn the above into an h2. three is an h3. Two new blank lines become p tags etc. There's a bunch of different markdown processors, they each have some differences. Slack's is very limited, Githubs is really extensive. Especially with code. make sure to choose the right language on github when adding code blocks.

## Here's the guide

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

Here's an online editor so you can check to make sure it your docs look sexy with no formatting errors.

http://dillinger.io/

*I couldn't find one that output html as a preview :( but this is better for most editing purposes.*

## Task

Since markdown is so easy to wrap your head around, this task will be using some slightly more advanced git features to begin generating documentation using markdown. I've included a `task.md` file that's the same as the index.html before you formatted it last time. Run through and mark it up to match the tags used the file I corrected.

Do a fresh pull request since I've updated the remote. 
	`$ git pull --all`

Create a new branch called 3-markdown

You want the content tags to closely match the index.html file linked above. Edit and push the file back for review. 

### 2nd Task

1. First make an archive of this readme as task.md
	`$ mv README.md task.md && touch README.md`
2. Create a new blank README.md
3. Format all of your notes thus far into logical sections using markdown

Create a new readme for each of the lessons so far and save the old readme as task.md

1. 1-learning-git
2. 2-basic-html
3. 3-markdown

make sure when pushing each branch back that you are only pushing that branch, so something like:

example: `git push origin 1-learning-git`

We are going to use the branches on github to store all of your notes by section.

Include things like best practices you come across, your process, useful shortcuts and code snippets, set up or plugins you downloaded for each section. Keep it organized and readable so that I understand by reading through it. I'll be able to give you feedback and correct any misconceptions quickly. 

Then when you want to reference something you can go here:

https://github.com/PuddletownDesign/russ/branches

and it will be layed out like the chapters of a book

### There is a very handy cheaty way to do this fast :)

In the markdown editor you can import readme files out of branches by linking the github account. To better learn the syntax you can just edit these files directly on github as well. Lastly do the above method with all the individual branch pushes if you wanna get super geeky with it.

* http://dillinger.io/

I recommend it as it makes writing markdown stylish and easy and it's straight up published to the cloud. :) It's really hard for a billion console commands to beat this set up.

