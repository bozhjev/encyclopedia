---
title: How to edit 
permalink: edit
layout: default
---

# How to edit 

The aim of Indexmod Encyclopedia to simplify wiki syntax for a pretty and light format. Following checklist explains few steps of creating and editing beautiful articles in Indexmod Encyclopedia.

# Page structure 

See [Page template](page-template.md) for details. Every page is written with [Markdown](https://daringfireball.net/projects/markdown/syntax) and must have **front matter** area set with triple-dashed lines. 

`---`

`title: How to edit`

`permalink: edit`

`layout: default`

`---`

Above sample points a **front matter** of the page **How to edit**. A **front matter** may contain **page title**, **permalink**, **layout** and other meta data. The visible area of the page contains **Title** and **Front** section, an image with captions and credits, **Conspectus** section, **See also** section with links to another pages and **Footnotes** section, **Edit this page** link.

# Title  


`# Aberdeen Fashion Week` 


`# Tailor, Victoria` 


`# Duma, Miroslava (publisher)` 


Includes the subject's name **Aberdeen Fashion Week**, surname and name **Tailor, Victoria** and may be added with dissimulation with round brackets **Tailor, Victoria (designer)**. 

# Front

`(Born 1968, Paris)` 

`(Est. 2012, Moscow)` 

Starts with **(Born, Est. 1999, city)** beginner in round brackets. Following one-two sentences of description front ends with footnote links styled with **squared brackets** <span id="a1">[\[1\]](#f1)</span>, <span id="a2">[\[2\]](#f2)</span>, <span id="a3">[\[3\]](#f3)</span>. 

`<span id="a1">[\[1\]](#f1)</span>` 

Will be rendered:

<span id="a1">[\[1\]](#f1)</span>


# Image, caption, and credits

This is image link code:

`![](/encyclopedia/images/image-name.jpg)`


`**Image caption**`

Will be rendered:

**Image caption**


`*Photo: [Photographer name](photographer-name)` 

`/ [Source name](edition-name)*`

Will be rendered:

*Photo: [Photographer name](photographer-name) / [Source name](edition-name)*

Every image must be described as much possible detailed and styled with **bold font**. Credits line starts with **photographer's name** styled italic with an active link and after slash separator a source, or/and edition name. Links may also be pointed to **not existing pages** with syntax **photographer-name** or **edition-name**.

# Conspectus

Conspectus is a way to style some data and lists like events or places in table. 

`|Year|City|`

`|---|---|`

`|2014|Tokyo|`

`|2015|Moscow|`

`|2017|Paris|`

Will be rendered:

|Year|City|
|----|-----|
|2014|Tokyo|
|2015|Moscow|
|2017|Paris|

# See also 

This section connects your page with others pages in Indexmod Encyclopedia. Use following template combining list and link styling syntax. The code:

`+ [See also title one](page-template-1)`

Will be rendered:

+ [See also title one](page-template-1)


# Footnotes 

`[[1]](#a1) <span id="f1"></span>` 

`[Article 1 (Author 1)]`

`(http://example.net/article)`

Will be rendered:

[[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)](http://example.net/article)


Connect some text using short links <span id="a1">[\[1\]](#f1)</span>, <span id="a2">[\[2\]](#f2)</span>, <span id="a3">[\[3\]](#f3)</span> with links and source in **Footnote** edit. Kepp numbering in links organized: [[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)](http://example.net/article)


# Prose.io editor linking

`[Edit this page]` 

`(http://prose.io/#indexmod/encyclopedia/edit/master/edit.md)`

Will be rendered:

[Edit this page](http://prose.io/#indexmod/encyclopedia/edit/master/edit.md)

You may edit every page in Prose.io editor using above sample link with **/page-name.md**. To push edit changes you may need authorize as [GitHub](https://github.com/join) user.
