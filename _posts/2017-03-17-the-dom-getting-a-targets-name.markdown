---
layout: posts
title:  "The DOM: Getting a target's name"
tags: Javascript
---

#### Question:
In the markup below what is the node name of the element? (Pay attention to the case.) `<img src="http://www.wikipedia.org">`

#### Answer:
IMG

#### Question:
In the markup below, what is the node value of the element?
`<img src = "http://www.wikipedia.org">`

#### Answer:
`null`

#### Question:
What is the node name of the first child of the element?
{% highlight javascript %}
<p>Hello world!</p>
{% endhighlight %}

#### Answer:
`#text`

#### Question:
Fill in the blank. The value of the first child of the first element is "______" `<p>Hello<strong> world!</strong></p>`

#### Answer:
Hello

#### Question:
Get the name of a node that has been assigned to the variable `targetNode` and assign it to the variable `nName`, which hasn't been declared beforehand.

#### Answer:
`var nName = targetNode.nodeName;`

#### Question:
In a single statement get the name of the second child of an element with the id "d2" and assign it to the variable `child2`, which hasn't been declared beforehand.

#### Answer:
`{% highlight javascript %}
var child2 = document.getElementById("d2").childNodes[1].nodeName;
{% endhighlight %}`

#### Question:
Check the name of the variable `nodeToCheck` to see if it's a text node. If so, get its text content (value) and assign it to the variable `content`, which hasn't been declared beforehand.

#### Answer:
`{% highlight javascript %}
if (nodeToCheck.nodeName === "#text") {
  var content = nodeToCheck.nodeValue;
}
{% endhighlight %}`

#### Question:
Code the first line of an if statement that tests if a node assigned to the variable `mysteryNode` is a link. Assume that the name is in uppercase.

#### Answer:
`if (mysteryNode.nodeName === "A") {`

#### Question:
Working your way down the DOM hierarchy, get the value of the document's title text and assign it to the variable `dTitle`, which hasn't been declared beforehand. (In this document the title is the first child of the head.)

#### Answer:
`var dTitle = document.childNodes[0].childNodes[0].childNodes[0].
childNodes[0].nodeValue;`
