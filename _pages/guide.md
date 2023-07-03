---
layout: page
title: Guide
permalink: /guide/
image: '/images/guide.jpeg'
---

## Syntax

**Bold** 

*Italic*

~~Strikethrough~~ <!--- 在单词的左右两边加两个～ -->

***

## Headings by default:

# H1 Default styles for headings
## H2 Default styles for headings
### H3 Default styles for headings
#### H4 Default styles for headings
##### H5 Default styles for headings
###### H6 Default styles for headings

***

## Lists

### Ordered list example:

1. This is the first item
2. This is the second item
3. This is the third item
4. This is the fourth item
5. This is the fifth item

***

### Unordered list example:

- This is the first item
- This is the second item
- This is the third item
- This is the fourth item
- This is the fifth item

也可以用 *

* This is the first item

***

## Table

<div class="table-container">
  <table>
    <tr><th>Header 1</th><th>Header 2</th><th>Header 3</th><th>Header 4</th><th>Header 5</th></tr>
    <tr><td>Row:1 Cell:1</td><td>Row:1 Cell:2</td><td>Row:1 Cell:3</td><td>Row:1 Cell:4</td><td>Row:1 Cell:5</td></tr>
    <tr><td>Row:2 Cell:1</td><td>Row:2 Cell:2</td><td>Row:2 Cell:3</td><td>Row:2 Cell:4</td><td>Row:2 Cell:5</td></tr>
    <tr><td>Row:3 Cell:1</td><td>Row:3 Cell:2</td><td>Row:3 Cell:3</td><td>Row:3 Cell:4</td><td>Row:3 Cell:5</td></tr>
    <tr><td>Row:4 Cell:1</td><td>Row:4 Cell:2</td><td>Row:4 Cell:3</td><td>Row:4 Cell:4</td><td>Row:4 Cell:5</td></tr>
    <tr><td>Row:5 Cell:1</td><td>Row:5 Cell:2</td><td>Row:5 Cell:3</td><td>Row:5 Cell:4</td><td>Row:5 Cell:5</td></tr>
    <tr><td>Row:6 Cell:1</td><td>Row:6 Cell:2</td><td>Row:6 Cell:3</td><td>Row:6 Cell:4</td><td>Row:6 Cell:5</td></tr>
  </table>
</div>

***

## Quotes

#### A quote looks like this:

> "The heaviest penalty for declining to rule is to be ruled by someone inferior to yourself."
> 
> <cite>Plato, *The Republic*</cite>

>“Jump above calculations, group the operations, classify them according to their complexities rather than their appearance; this, I believe, is the mission of future mathematicians.”
>
> -- <cite>Évariste Galois</cite>

***



## Syntax Highlighter

{% highlight css %}
body {
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vw;
  background-color: #1c2021;
}

li {
  width: 200px;
  min-height: 250px;
  border: 1px solid #000;
  display: inline-block;
  vertical-align: top;
  margin: 5px;
}
{% endhighlight %}

***

## Code Block

```
print('hi Ann')
```

***

## Images

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/an-1.jpeg">
    <img src="/images/an-2.jpeg">
    <img src="/images/an-3.jpeg">
    <img src="/images/an-4.jpeg">
    <img src="/images/an-5.jpeg">
    <img src="/images/an-6.jpeg">
  </div>
  <em>Gallery</em>
</div>

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/09.jpg">
    <img src="/images/06.jpg">
    <img src="/images/03.jpg">
    <img src="/images/08.jpg">
    <img src="/images/05.jpg">
    <img src="/images/11.jpg">
  </div>
  <em>Gallery / <a href="https://unsplash.com/" target="_blank">Unsplash</a></em>
</div>

![ocean]({{site.baseurl}}/images/an-2.jpeg)
*Photo by [Ann](https://sianren.com)*

***

## Youtube Embed

可以嵌入Youtube视频，如下，但是要在链接中加上embed, 这个视频是讲

原链接：
    https://www.youtube.com/IV3dnLzthDA

嵌入链接：
    https://www.youtube.com/embed/IV3dnLzthDA

<p><iframe src="https://www.youtube.com/embed/IV3dnLzthDA" frameborder="0" allowfullscreen></iframe></p>

***
