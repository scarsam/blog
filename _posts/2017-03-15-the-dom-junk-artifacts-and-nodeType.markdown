---
layout: posts
title:  "The DOM: Junk artifacts and nodeType"
tags: Javascript
---

#### Question:
Some browsers interpret whitespace in markup as nodes. What type of nodes are they?

#### Answer:
text

#### Question:
If the node is a text node, what is the value of nType?
`var nType = targetNode.nodeType;`

#### Answer:
3

#### Question:
If the node is an element node, what is the value of nType?
`var nType = targetNode.nodeType;`

#### Answer:
1

#### Question:
In HTML markup whitespace is created by some tabs, spaces,
and ______________.

#### Answer:
carriage returns

#### Question:
Revise this markup to "hide" all the whitespace from the browser, while still keeping it on 3 lines.
{% highlight javascript %}
<p>
Hello world!
</p>
{% endhighlight %}
#### Answer:
{% highlight javascript %}
<p
>Hello world!</p
>
{% endhighlight %}

#### Question:
Minify this markup.
{% highlight javascript %}
<p>
Hello world!
</p>
{% endhighlight %}

#### Answer:
{% highlight javascript %}
<p>Hello world!</p>
{% endhighlight %}

#### Question:
Write the first line of an if statement that tests whether a node represented by the variable n is a text node.

#### Answer:
`if (n.nodeType === 3) {`

#### Question:
Find the number of children of a parent represented by the variable p and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var numChildren = p.childNodes.length;`

#### Question:
Write a for loop that checks to see if the next child of a parent represented by a variable `p` is an element node. If it is, break out of the loop. Begin by assigning the number of children of the parent to a variable, which hasn't been declared beforehand. Use the variable to limit the number of loops. Use the most common loop specifications.

#### Answer:
{% highlight javascript %}
var numKids = p.childNodes.length;
for (var i = 0; i < numKids; i++) {
  if (p.childNodes[i].nodeType === 1) {
    break;
  }
}
{% endhighlight %}
