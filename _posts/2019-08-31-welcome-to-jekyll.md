---
layout           : post
title            : "Welcome to Jekyll (no sidebar)"
date             : 2019-08-31 13:52:31 +0200
last_modified_at : 2019-09-19 13:52:31 +0200
categories       : ['Edge case', Markup]
permalink        : /welcome-to-jekyll/
sidebar          : false
latex: true
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby linenos %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

This is a Python snippet!

{% highlight python %}
def print_hi(name):
	print("Hi", name)
print_hi('Gerard')
{% endhighlight %}

{% highlight css linenos %}
.highlight .sc { color: #aa5500  } /* Literal.String.Char */
.highlight .dl { color: #aa5500  } /* Literal.String.Delimiter */
.highlight .sd { color: #aa5500  } /* Literal.String.Doc */
{% endhighlight %}

And now let's try with some LaTeX using Katex!

$$\frac{1}{3}=0.\overline{3}\approx0.33333...$$

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
