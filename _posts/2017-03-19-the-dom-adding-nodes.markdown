---
layout: posts
title:  "The DOM: Adding nodes"
tags: Javascript
---

#### Question:
What is the keyword for creating a new div?

#### Answer:
`createElement`

#### Question:
What is the keyword for adding class = "pretty" to an image tag?

#### Answer:
`setAttribute("class", "pretty");`

#### Question:
What is the keyword for creating a string that will be the child of a paragraph?

#### Answer:
`createTextNode`

#### Question:
What is the keyword for adding text content to a paragraph?

#### Answer:
appendChild

#### Question:
Create a div and assign it to a variable of your choosing, which hasn't been declared beforehand.

#### Answer:
`var newDiv = document.createElement("div");`

#### Question:
Create a new text node with a string of your choosing and assign it to a variable of your choosing, which hasn't been declared beforehand.

#### Answer:
`var txt = document.createTextNode("Me Tarzan");`

#### Question:
Add a text node represented by a variable of your choosing to a parent represented by another variable of your choosing.

#### Answer:
`parentNode.appendChild(newTextNode);`

#### Question:
A new `<a>` node has been created and assigned to the variable `newLink`. Add an attribute to it that takes the user to wikipedia.org when clicked.

#### Answer:
`newLink.setAttribute("href", "http://www.wikipedia.org");`

#### Question:
In 3 statements, create a paragraph and insert some text content into it.

#### Answer:
{% highlight javascript %}
var newParagraph = document.createElement("p");
var newText = document.createTextNode("LOL");
newParagraph.appendChild(newText);
{% endhighlight %}
