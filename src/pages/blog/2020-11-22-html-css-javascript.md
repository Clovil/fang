---
templateKey: blog-post
title: HTML, CSS & JAVASCRIPT
date: 2020-11-22T07:36:56.995Z
description: What are these three languages refer to?
featuredpost: true
featuredimage: /img/html_and_css.png
tags:
  - tech
  - web
  - HTML
  - CSS
  - JavaScript
---
When we browse the web and stumble on websites, we are looking at how these 3 languages comprise a website. 

Understanding how these 3 interacts will be a key element if you are pursuing a web developer career. 

This is pretty much the gist of HTML, CSS, and JavaScript:

* HTML is for adding meaning to raw content by marking it up.
* CSS is for formatting that marked up content.
* JavaScript is for making that content and formatting interactive.

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



This is part 1 of Introduction of HTML and CSS. I found out that the tutorial is very friendly for beginners who wants to learn more about web development or HTML and CSS in general.** [Link](https://www.internetingishard.com/html-and-css/introduction/)**