---
title: What Is jekyll-latex?
author: John Doe
layout: post
---

# Table of Contents
* TOC
{:toc}

```
{% raw %}
# Table of Contents
* TOC
{:toc}
{% endraw %}
```

# HTML Elements

## Text Formatting

This sentence is **bold**. This sentence is *italic*. <small>Small</small> text is for fine print. Your copy can also be <sub>subscripted</sub> and <sup>superscripted</sup>, <ins>inserted</ins>, ~~deleted~~, or <mark>highlighted</mark>. You would use a [hyperlink](https://github.com/ryanmcdermott/jekyll-latex) to go to a new page. Keyboard input elements like <kbd>Cmd + Shift</kbd> are used to display textual user input.

```
This sentence is **bold**. This sentence is *italic*.
<small>Small</small> text is for fine print. Your
copy can also be <sub>subscripted</sub> and
<sup>superscripted</sup>, <ins>inserted</ins>,
~~deleted~~, or <mark>highlighted</mark>. You would
use a [hyperlink]
(https://github.com/ryanmcdermott/jekyll-latex) to
go to a new page. Keyboard input elements like
<kbd>Cmd + Shift</kbd> are used to display textual
user input.
```

## Definition Lists
First Term
: This is the definition of the first term.

Triple Integral
: $\iiint_V \mu(u,v,w) \,du\,dv\,dw$

<pre>
<code>
First Term
: This is the definition of the first term.

Triple Integral
: $\iiint_V \mu(u,v,w) \,du\,dv\,dw$

</code>
</pre>

## Blockquotes

> Give me six hours to chop down a tree and I will spend the first four sharpening the axe.
<cite>— Abraham Lincoln</cite>

<pre>
<code>
&gt; Give me six hours to chop down a tree and I will spend the first four
sharpening the axe.
&lt;cite&gt;— Abraham Lincoln&lt;/cite&gt;
</code>
</pre>

## Tables

|Header 1|Header 2|Header 3|
|--- |--- |--- |
|Description 1|Description 2|Description 3|
|Description 1|Description 2|Description 3|
|Description 1|Description 2|Description 3|

<pre>
<code>
|Header 1|Header 2|Header 3|
|--- |--- |--- |
|Description 1|Description 2|Description 3|
|Description 1|Description 2|Description 3|
|Description 1|Description 2|Description 3|
</code>
</pre>

## Images

{% include image.liquid url="/assets/latex_image_example.jpeg" description="Mountain landscape by John Towner." %}

```
{% raw %}
{% include image.liquid
    url="/assets/latex_image_example.jpeg"
    description="Mountain landscape by John Towner."
%}
{% endraw %}
```

## Lists

### Unordered List
- List Item 1
- List Item 2
- List Item 3

### Ordered List

1. List Item 1
1. List Item 2
1. List Item 3

```
{% raw %}
### Unordered List
- List Item 1
- List Item 2
- List Item 3

### Ordered List

1. List Item 1
1. List Item 2
1. List Item 3
{% endraw %}
```
