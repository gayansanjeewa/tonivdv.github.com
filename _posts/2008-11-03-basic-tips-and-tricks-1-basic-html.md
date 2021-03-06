---
title: 'basic tips and tricks: 1. Basic HTML'
author: kennethvr
layout: post
deprecated: true
permalink: /2008/11/03/basic-tips-and-tricks-1-basic-html/
syntaxhighlighter_encoded:
  - 1
categories:
  - css
  - html
  - Tips and Tricks
tags:
  - basic
  - css
  - html
  - lessons
  - tips
---
There seems to be a big lack of knowledge in the field of basic web design, therefore I decided to write a step-by-step web design tutorial. Every post will be a new chapter in development; I will try to give you a fresh view on what really matters and is interesting for starting users. We&#8217;ll start with the basics like tags in html and go on with CSS; the future will tell us how far we get. The point is to share my experience with you guys, not to teach you every detail, if you are completely fresh to HTML and CSS; you better take a look at w3schools first. ([http://www.w3schools.com][1])

So let&#8217;s start off with our first post: BASIC HTML

First off all, if you want to learn HTML and CSS, try not to use the design view of programs to often. It&#8217;s very easy to create simple pages with those design views, but you won&#8217;t learn the code, and that&#8217;s the important stuff you need to know. So let&#8217;s take a look at basic fresh html code generated by Dreamweaver:

<pre class="brush: xml; title: ; notranslate" title="">&lt;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"&gt;
&lt;html xmlns="http://www.w3.org/1999/xhtml"&gt;
&lt;head&gt;
&lt;meta http-equiv="Content-Type" content="text/html; charset=utf-8" /&gt;
&lt;title&gt;Untitled Document&lt;/title&gt;
&lt;/head&gt;

&lt;body&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre>

So what is really important in this example?

As you can see, html is completely built up with tags and every tag is written inside the tag it is containing to. You can see that the head and body tag are within the html tag, because the html tag is the whole page and the header and body are in it.

The head tags are simply to give information like the name of the page (now ‘Untitled Document&#8217;) and include the necessary files (that&#8217;s for later). The real important one is the body tag because that is what the user will see. Whatever you will write within these tags, will be displayed on the screen of the person that visits your website.

So if we write <body>test</body> the user will get an empty, blank screen with test written on it. Easy, isn&#8217;t it? So now you can write whatever you want in the page. The tricky part is the layout of the text.

Layout of a text is also done with the tags as they are written in the first example. So when you want to write for example this is **bold** this is *italic* and this is <span style="text-decoration: underline;">underlined</span>, you will have to write this:

This is <b>bold</b> this is <i>italic</i> and this is <u>underlined</u>

As you can see every type of layout has its own specific layout tags b for bold, I for italic and u for underline. When using tags, be sure that you always close the tags just as in the example.

Like there are tags for text layout, there are also tags for line breaks and paragraphs. When you are writing long texts with paragraphs in it, always try to write your text within the <p></p> tags. Don&#8217;t use 2 <br /> tags instead; this is a very often made mistake. This is for the simple reason that <br /> isn&#8217;t the same as a paragraph, it doesn&#8217;t react the same way for every user, a paragraph tag does. So use your <br /> tags wisely within the <p> tags like so:

<pre class="brush: xml; title: ; notranslate" title="">This is a long text and when we go to a new line within the paragraph we use a line break
So this will be displayed on a new line within the same paragraph

This is a second paragraph that will be displayed

</pre>

This will result in:

This is a long text and when we go to a new line within the paragraph we use a line break  
So this will be displayed on a new line within the same paragraph

This is a second paragraph that will be displayed

The last thing for today is the headings which are used to display titles. Just like the paragraph tag you can use the heading tag: <h1></h1><h2></h2>. H stands for heading and the numbers are the scale that the heading is displayed in, 1 being the biggest and 6 being the smallest.

That was it for today my friends, this was the easiest part, in next lessons we will talk about topics like:

DIV vs. Tables  
CSS and how to use it properly  
debugging and testing  
and much more

 [1]: http://www.w3schools.com/