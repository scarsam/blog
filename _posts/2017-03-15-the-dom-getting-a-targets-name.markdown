---
layout: posts
title:  "The DOM: Getting a target's name"
tags: Javascript
---

#### Question:
In the markup below what is the node name of the element? (Pay attention to the case.)
`<img src="http://www.wikipedia.org">`

#### Answer:
firstChild

#### Question:
The node assigned to the variable n has 5 children. What is the alternative to `n.childNode[4]`?

#### Answer:
`n.lastChild`

#### Question:
The second paragraph has been assigned to the variable `p2`. Target the div that encloses it using the variable, and assign the target to another variable, which hasn't been declared beforehand.
{% highlight javascript %}
<div>
  <p>Have fun.</p>
  <p>Be careful.</p>
</div>
{% endhighlight %}

#### Answer:
`var x = p2.parentNode;`

#### Question:
DOM siblings are nodes that share the same _______.

#### Answer:
parent

#### Question:
Code this the alternate way.
{% highlight javascript %}
var tNode = pNode.childNodes[0];
{% endhighlight %}

#### Answer:
{% highlight javascript %}
var tNode = pNode.firstChild;
{% endhighlight %}

#### Question:
The node represented by pNode has 10 children. Code this the alternate way.
{% highlight javascript %}
var tNode = pNode.childNodes[9];
{% endhighlight %}

#### Answer:
{% highlight javascript %}
var tNode = pNode.lastChild;
{% endhighlight %}

#### Question:
The first paragraph, a child of parentNode, has been assigned to the variable p1. Target the next child of parentNode, and assign it to the variable tNode, which hasn't been declared beforehand.

#### Answer:
`var tNode = p1.nextSibling;`

#### Question:
The first child of parentNode has been assigned to the variable p1. Using p1 as a reference, target the third child of parentNode, and assign it to the variable tNode, which hasn't been declared beforehand. Use `nextSibling`.

#### Answer:
`var tNode = p1.nextSibling.nextSibling;`

#### Question:
Write the first line of an if statement that checks to see if there is a child before the node represented by n that shares the same parent. Use `previousSibling`.

#### Answer:
`if (n.previousSibling !== null) {`
