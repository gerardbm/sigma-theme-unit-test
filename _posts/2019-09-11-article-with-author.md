---
layout: post
title: Article with author + latex + sidebar left + custom excerpt
permalink: /article-with-author/
author: Doctor Jekyll
categories: 
  - Edge case
excerpt: >-
  This is a manual excerpt text.
robots: index,follow
keywords: 
  - Keyword 1
  - Keyword 2
  - Keyword 3
latex: true
image: images/unsplash-image-9.jpg
sidebar: left
---

This is a demo of all styled elements in Jekyll Now. 

[View the markdown used to create this post](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md).

<p>Lorem ipsum dolor sit amet, <a title="test link" href="#">test link</a> adipiscing elit. <strong>This is strong.</strong> Nullam dignissim convallis est. Quisque aliquam. <em>This is emphasized.</em> Donec faucibus. Nunc iaculis suscipit dui. 5<sup>3</sup> = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. <cite>The New York Times</cite> (That’s a citation). Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.</p>

$$\frac{1}{3}$$

<p><abbr title="Hyper Text Markup Language">HTML</abbr> and <abbr title="Cascading Style Sheets">CSS</abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.  Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. To copy a file type <code>COPY <var>filename</var></code>. <del>Dinner’s at 5:00.</del> <ins>Let’s make that 7.</ins></p>

<p>The <a href="#">a element</a> example <br />
The <abbr>abbr element</abbr> and <abbr title="Title text">abbr element with title</abbr> examples <br />
The <b>b element</b> example <br />
The <cite>cite element</cite> example <br />
The <code>code element</code> example <br />
The <del>del element</del> example <br />
The <dfn>dfn element</dfn> and <dfn title="Title text">dfn element with title</dfn> examples <br />
The <em>em element</em> example <br />
The <i>i element</i> example <br />
The <ins>ins element</ins> example <br />
The <kbd>kbd element</kbd> example <br />
The <mark>mark element</mark> example <br />
The <q>q element <q>inside</q> a q element</q> example <br />
The <s>s element</s> example <br />
The <samp>samp element</samp> example <br />
The <small>small element</small> example <br />
The <span>span element</span> example <br />
The <strong>strong element</strong> example <br />
The <sub>sub element</sub> example <br />
The <sup>sup element</sup> example <br />
The <var>var element</var> example <br />
The <u>u element</u> example</p>

This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Header 2 (H1 is reserved for post titles)##

### Header 3

#### Header 4

A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>

* A bulletted list
- alternative syntax 1
- alternative syntax 2
  - an indented list item
  - an indented list item
  - an indented list item
    - an indented list item
    - an indented list item
    - an indented list item
- alternative syntax 3
- alternative syntax 4
- alternative syntax 5
- alternative syntax 6

This is a table:

| Column 1 | Column 2 | Column 3 |
|:----------|:---------:|----------:|
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |
|===========|===========|===========|
| Column 1 | Column 2 | Column 3 |

Inline markup styles: 

- _italics_
- **bold**
- `code()` 
 
> Blockquote
>> Nested Blockquote 

> Syntax highlighting can be used by wrapping your code in a liquid tag like so yeah, it's nice. Syntax highlighting can be used by wrapping your code in a liquid tag like so yeah, it's nice. Syntax highlighting can be used by wrapping your code in a liquid tag like so yeah, it's nice. Syntax highlighting can be used by wrapping your code in a liquid tag like so yeah, it's nice. Syntax highlighting can be used by wrapping your code in a liquid tag like so yeah, it's nice.

Syntax highlighting can be used by wrapping your code in a liquid tag like so:

{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}  

creates...

{% highlight javascript linenos %}
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{% endhighlight %}
 
Use two trailing spaces  
on the right  
to create linebreak tags  
 
Finally, horizontal lines
 
----

****
