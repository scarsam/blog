---
layout: posts
title:  "The DOM: Attributes"
tags: Javascript
---

#### Question:
Fill in the blank.
In the markup below `src="http://www.wikipedia.org"`
is an _______ of the element `img`.
`<img src="http://www.wikipedia.org">`

#### Answer:
attribute

#### Question:
Fill in the blank. In the following markup src is the _______ of the attribute.
`<img src="http://www.wikipedia.org">`

#### Answer:
name

#### Question:
Fill in the blank. In the following markup `"http://www.wikipedia.org"` is the _______ of the attribute.
`<img src="http://www.wikipedia.org">`

#### Answer:
value

#### Question:
In the following markup, how many attributes does the element have? (Answer with a numeral.)
{% highlight javascript %}
<h1 id="main" class="normal" style="text-decoration:underline;">This <em>is</em> important!></h1>
{% endhighlight %}

#### Answer:
3

#### Question:
A div has been assigned to the variable tDiv. Find out if it has an attribute named "style" and assign the result to the variable hasStyle, which hasn't been declared beforehand.

#### Answer:
`var hasStyle = tDiv.hasAttribute("style");`

#### Question:
A div has been assigned to the variable tDiv. It has a class attribute. Find out what class has been assigned to it. Assign that to the variable divClass, which hasn't been declared beforehand.

#### Answer:
`var divClass = tDiv.getAttribute("class");`

#### Question:
Give an image that has been assigned to the variable `pic1` a new source, next-image.png, by manipulating an attribute.

#### Answer:
`pic1.setAttribute("src", "next-image.png");`

#### Question:
In a single statement, find out the address of a link whose id is "info" and assign it to the variable ad, which hasn't been declared beforehand.

#### Answer:
`var ad = document.getElementById("info").getAttribute("href");`

#### Question:
If the element assigned to the variable e doesn't have a class, set its class to "misc".

#### Answer:
{% highlight javascript %}
if (e.hasAttribute("class") === false) {
  e.setAttribute("class", "misc");
}
{% endhighlight %}`
