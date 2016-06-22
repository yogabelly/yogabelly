---
# Don't edit the layout line
layout: blogpost
# Title of the article
title: Some title goes here...
# Who wrote it? Aaron / Will / etc.
author: Aaron
# Remember to name the file as follows: YYYY-MM-DD-some-title-goes-here.md

# The following text is formatted in Markdown. Read about the syntax here:
# https://help.github.com/articles/basic-writing-and-formatting-syntax/
---

Markdown is a very simple language.
Taking newlines in markdown does not make a newline in the article, so feel free
to take a new line whenever suits you.
To make a new paragraph, leave a line blank.

To emphasize some text put *stars around it.*
To bold some text put **two stars around it.**
To make some text look kind of computery, put `back-ticks around it`.

To make a list, use hyphens or asterisks as bullets as follows:

- list item 1
- list item 2

Numbered lists use the number-period format as follows:

1. list item 1
2. list item 2

You can insert a quote by using angle-brackets:

> This is a very famous quote by somebody or other.
> Normal Markdown rules apply in here, so to take a new line leave a line blank
> like so:
>
> If you want to attribute the quote, do it like this:
>
> -- <cite>Some Person</cite>

Links use this format:
[linktext](http://www.example.com/page.html)

Images use this format:
![image alt text](/images/blog/example/image.jpg)

If you need to do something fancy with an image (like give it a float) you can
also use regular HTML.<image align="left" src="/images/blog/example/image.jpg">

When you use images, keep an eye on the image size. The blog is never going to
display an image as wider than about 700px, so you should resize images to be
at most 700px wide to make them load faster.

Note that when you include an image, you have to put it somewhere. I've created
a folder called `/images/blog/` where you can put images to link to. You don't
need to follow any particular structure, but it's best if you keep it organized.
You could use one folder for every blog post, or one folder for every month, or
whatever you want. I've put the image from this example into a folder called
`example`.

You can also have various levels of headings, using varying numbers of the #
symbol at the beginning of a line:

# First level title

## Second level title

### Third level title

#### Fourth level title

##### Fifth level title

Many text-editors have syntax highlighting for Markdown files. You may find it
helpful to use such an editor. Some examples include:

- [Textmate](http://macromates.com/)
- [Atom](htts://atom.io)
- [SublimeText](http://www.sublimetext.com/)

That's about it!
