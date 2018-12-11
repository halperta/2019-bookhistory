---
layout: post
title: "Writing in Markdown"
modified:
categories: tutorial
excerpt:
tags: []
author: halperta
image:
  feature:
---

# Writing an article in markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a simple formatting language for writing text. It works a lot like HTML, only it's a lot easier to use.

You'll be writing your blog post in Markdown. 

You have two options for composing the post:
1. Compose in GitHub: Follow steps 1-4 in the `Publishing a Digital Review` tutorial. Once you've created a new file (in step four) you can compose the file directly in GitHub, using the "commit" feature to save the file online.

2. You can also compose your post using a plain text editor, and then copy and paste it into the GitHub repository. Notebook is one popular program. I like to use [Sublime](https://www.sublimetext.com/). Follow these instructions to get started, or [view the markdown version of this page](http://www.halperta.com/criticalarchives/tutorial/writing-in-markdown/).

## YAML header
Your file should begin with a header that looks exactly like this (including the dashes):

```
---
layout: post
title: "ENTER YOUR TITLE HERE (in quotes)"
modified:
categories: blog
excerpt: "ENTER A PULL QUOTE HERE (in quotes)" (it will show up on the Reviews home page)
tags: []
author: ENTER YOUR AUTHOR ID HERE (no quotes)
image:
  feature:
---
```

## Content
Below the YAML header, you can start composing your review just as you normally would. The only difference is that you'll use a very simple form of encoding to add stylistic features like italics, create headings, or add other kinds of formatting.

You can find detailed instructions on how to write in Markdown [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), or use the following tips:  

```
Headers:  
    # Heading One  
    ## Heading Two  
    ### Heading Three (etc)  

Formatting:  
	*italics*  
	**bold**  

Links:  
	[link text in brackets](url-in-parentheses)

Line Breaks:  
	End the previous line with two spaces,  
	then begin writing on the following line to create a line break.  

Paragraphs:
	Enter a blank line after the end of a paragraph...  

	...before starting a new one.

Accents:  
	Accents and other diacritics (á, ñ, ü)  
	can be typed into the text as normal.

Lists:
	Use 
		* text
	to create a disordered list.
	Use 
		1. text
		2. text 
		3. text 
	to create an ordered list.

```
