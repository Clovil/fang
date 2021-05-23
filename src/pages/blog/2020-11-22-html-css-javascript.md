---
templateKey: blog-post
title: Introduction to HTML, CSS & JAVASCRIPT
date: 2020-11-22T07:36:56.995Z
description: "Courtesy of No. 1 of HTML & CSS is hard "
featuredpost: true
featuredimage: /img/html_and_css.png
tags:
  - tech
  - web
  - HTML
  - CSS
  - JavaScript
---
## What is HTML, CSS & JavaScript?

Whenever we hear these 3 keywords, they are always wrapped together. What do they mean? What do they look like? When we browse the web and looking on web pages, we are looking at how these 3 languages make up and comprise a website. 

Understanding how these 3 interacts will be a key element if you are trying to learn how a web page works. In my case, I am trying to learn how to create my own website from scratch.

This is pretty much the gist of HTML, CSS, and JavaScript:

* HTML = marking raw content
* CSS = formatting specified marked up content
* JavaScript = making marked up content and formatting interactive (actions and animations)

![Courtesy of HTML & CSS is hard](/img/html_css_and_javascript.png "Courtesy of HTML & CSS is hard")

**Example**

This is what HTML looks like for displaying a paragraph of text.

```html
<p id='some-paragraph'>
  This is a small paragraph. A paragraph might consist more than 1 sentence. That is why I am writing this example.
</p>
```

CSS example when you set the size and color of that paragraph.

```css
p {
  font-size: 20px;
  color: blue;
}
```

The appearance of a website is determined and controlled by HTML and CSS. In you want to have interaction within a website, that is where JavaScript takes a part in building a website.

Below is an example of what happens when user clicks a paragraph that we wrote above.

```javascript
var p = document.getElementById('some-paragraph');

p.addEventListener('click', function(event) {
  p.innerHTML = 'You clicked it!';
  }
);
```



## Learning vs creating

Learning and mastering HTML, CSS, and JavaScript is only a prerequisite to create your own website. It does not mean that by mastering these you will be able to create and run a website.

There are other skills needed for me to run my own website.

* Organizing the HTML
* Starting a web server
* Moving files from your local computer to your web server
* Reverting to a previous version when you screw something up
* Pointing a domain name at your server

![Courtesy of HTML & CSS is hard](/img/running_a_website.png "Courtesy of HTML & CSS is hard")

Yeah... there are other materials that we need to learn. Though, this does not slow or hinder us down from trying to learn HTML and CSS.

We can compare how to create a website to how to print a book.

![Courtesy of HTML & CSS is hard](/img/website_comparison_printing.png "Courtesy of HTML & CSS is hard")

> Back in the days of the original printing press, printers created documents by arranging metal characters, dipping them in ink, and pressing them onto a piece of paper.
>
> In a lot of ways, that’s exactly what web developers do, except instead of arranging moveable type, they write HTML and CSS. We’re concerned with the same task as they were: conveying content in meaningful ways. We even deal with the same presentational issues they did, like selecting the font to use, setting the size of headings, and determining the space between lines of text.

That sums part 1 of Introduction of HTML and CSS. I found out that the tutorial is very friendly for beginners who wants to learn more about web development or HTML and CSS in general. You can take a look directly to **[HTML & CSS is hard](https://www.internetingishard.com/html-and-css/)** \[but it doesn't have to be]