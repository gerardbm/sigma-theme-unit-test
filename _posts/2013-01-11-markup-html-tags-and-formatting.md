---
layout: post
title: "Markup: HTML Tags and Formatting"
categories:
  - Markup
tags:
  - content
  - css
  - formatting
  - html
  - markup
---

A variety of common markup showing how the theme styles them.

# Header one

## Header two

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Stay hungry. Stay foolish.

Multi line blockquote with a cite reference:

> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.

<cite>Steve Jobs</cite> --- Apple Worldwide Developers' Conference, 1997
{: .small}

## Tables

| Employee         | Salary |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | $1     | Because that's all Steve Jobs needed for a salary.           |
| [Jane Doe](#)    | $100K  | For all the blogging she does.                               |
| [Fred Bloggs](#) | $100M  | Pictures are worth a thousand words, right? So Jane × 1,000. |
| [Jane Bloggs](#) | $100B  | With hair like that?! Enough said.                           |

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

```html
<a href="#" class="btn-success">Success Button</a>
```

[Default Button](#){: .btn-default}

[Red Button](#){: .btn-red}

[Orange Button](#){: .btn-orange}

[Green Button](#){: .btn-green}

[Teal Button](#){: .btn-teal}

[Blue Button](#){: .btn-blue}

[Purple Button](#){: .btn-purple}

[Pink Button](#){: .btn-pink}

[Inverse Button](#){: .btn-inverse}

```markdown
[Default Button](#){: .btn-default}
[Red Button](#){: .btn-red}
[Orange Button](#){: .btn-orange}
[Green Button](#){: .btn-green}
[Teal Button](#){: .btn-teal}
[Blue Button](#){: .btn-blue}
[Purple Button](#){: .btn-purple}
[Pink Button](#){: .btn-pink}
[Inverse Button](#){: .btn-inverse}
```

[X-Large Button](#){: .btn-default .btn-x-large}

[Large Button](#){: .btn-default .btn-large}

[Default Button](#){: .btn-default}

[Small Button](#){: .btn-default .btn-small}

```markdown
[X-Large Button](#link){: .btn-default .btn-x-large}
[Large Button](#link){: .btn-default .btn-large}
[Default Button](#link){: .btn-default}
[Small Button](#link){: .btn-default .btn-small}
```

[Default Button full width](#){: .btn-default .btn-block}

```markdown
[Default Button full widht](#){: .btn-default .btn-block}
```

## Notices

**Watch out!** You can also add notices by appending `{: .notice-info}` to a paragraph.
{: .notice-info}

**Watch out!** You can also add notices by appending `{: .notice-success}` to a paragraph.
{: .notice-success}

**Watch out!** You can also add notices by appending `{: .notice-warning}` to a paragraph.
{: .notice-warning}

**Watch out!** You can also add notices by appending `{: .notice-alert}` to a paragraph.
{: .notice-alert}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://apple.com "Apple").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
	margin: 0 0 5px;
	font-weight: bold;
	font-size: 38px;
	line-height: 1.2;
	and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.
