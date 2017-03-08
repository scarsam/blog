---
layout: posts
title:  "Events: mouse"
tags: Javascript
---

#### Question:
What is the keyword for detecting that the user is hovering over an element?

#### Answer:
`onMouseover`

#### Question:
What is the keyword for detecting that the user is no longer hovering over an element?

#### Answer:
`onMouseout`

#### Question:
When the user hovers over the image, it changes to 2.png. Complete the code.
`<img src="1.png" ______________________________`

#### Answer:
`<img src="1.png" onMouseover="src='2.png'">`

#### Question:
When the user stops hovering over the heading, the function gone executes. Fill in the blank.
`<h1 ________________>Get away from me!</h1>`

#### Answer:
`onMouseout="gone();"`

#### Question:
When the user hovers over the h2 heading that says "More" the function expand executes. Write the opening tag, the text, and the closing tag.

#### Answer:
`<h2 onMouseover="expand();">More</h2>`

#### Question:
When the user moves off the paragraph, the function gone executes. Code the opening tag.

#### Answer:
`<p onMouseout="gone();">`

#### Question:
When the user hovers over a button that says "Panic" an alert displays saying "Eeek!"

#### Answer:
`<input type="button" value="Panic" onMouseover="alert('Eeek!');">`

#### Question:
When the user hovers over a link to index.html, the color of the text changes to red. Code only the opening tag.

#### Answer:
`<a href="index.html" onMouseover="this.style.color='red';">`

#### Question:
When the user hovers over pic1.gif, it is replaced by pic2.gif. When the user moves off the image, it reverts to pic1.gif.

#### Answer:
`<img src="pic1.gif" onMouseover="src='pic2.gif'" onMouseout="src='pic1.gif'">`

#### Question:
Live coding exercise:
1) Code a button that, when hovered over, displays an alert.

#### Answer:
{% highlight javascript %}

<input type="button" value="Click me" onMouseover="alert('hello');">

{% endhighlight %}

#### Question:
Live coding exercise:
1) Write markup that displays the image janice-before.jpg. When the user hovers over the image, it is replaced by janice-after.jpg. When the user moves off the image, it reverts to janice-before.jpg.

#### Answer:
{% highlight javascript %}

<img src="janice-before.jpg" onMouseover="src='janice-after.jpg'" onMouseout="src='janice-before.jpg'">

{% endhighlight %}
