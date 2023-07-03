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

Markdown的语法以及逻辑和知乎几乎一模一样，所以你只要会用知乎的编辑器，就可以很快上手这个编辑器。而VS code也可以把它当作和word一样的文字编译器用，所以你可以在这里写作业，写作文，写日记，写博客，写论文，写代码，写什么都可以。

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

可以单独插入图片，如下：

![ocean]({{site.baseurl}}/images/an-2.jpeg)
*Photo by [Ann](https://sianren.com)*

也可以插入图片的gallery，如下， 但是注意到 会因为比例不一样，导致图片的大小不一样

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/an-1.jpeg">
    <img src="/images/an-2.jpeg">
    <img src="/images/an-3.jpeg">
    <img src="/images/an-4.jpeg">
    <img src="/images/an-5.jpeg">
    <img src="/images/an-6.jpeg">
  </div>
  <em>比例调整前的Gallery</em>
</div>

解决方法就是可以用电脑打开相册，然后照着一个比例去crop比如如下：

![crop]({{site.baseurl}}/images/crop_img.png)

***

这是一个比利一样的gallery的例子

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


***

## Youtube Embed

可以嵌入Youtube视频，如下，但是要在链接中加上embed, 这个视频是讲lead的。

原链接：
    https://www.youtube.com/IV3dnLzthDA

嵌入链接：
    https://www.youtube.com/embed/IV3dnLzthDA

<p><iframe src="https://www.youtube.com/embed/IV3dnLzthDA" frameborder="0" allowfullscreen></iframe></p>

***