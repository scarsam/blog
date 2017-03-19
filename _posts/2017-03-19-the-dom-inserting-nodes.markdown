---
layout: posts
title:  "The DOM: Inserting nodes"
tags: Javascript
---

#### Question:
The statement appends the node represented by `cNode` to the parent node represented by `pNode`. Fill in the blank.
`pNode.___________(cNode);`

#### Answer:
`pNode.appendChild(cNode);`

#### Question:
The statement inserts the node represented by `cNode` before the child represented by `node2`. The parent node is represented by `pNode`. Fill in the blank.
`pNode.insertBefore(cNode, _______);`

#### Answer:
`pNode.insertBefore(cNode, node2);`

#### Question:
When the following statement executes, what node comes before `cNode`?
`pNode.insertBefore(cNode, node2.nextSibling);`

#### Answer:
`node2`

#### Question:
In a single statement, eliminate the last node one level down from the element represented by `parentNode`.

#### Answer:
`parentNode.removeChild(parentNode.lastChild);`

#### Question:
Add a new node represented by a variable of your choice as the last child of a node represented by another variable of your choice. Don't use `insertBefore`.

#### Answer:
`parentNode.appendChild(newNode);`

#### Question:
Remove a node represented by a variable of your choosing from a parent represented by another variable of your choosing.

#### Answer:
`hello.removeChild(dance);`

#### Question:
Using variables of your choosing, insert a new node after an existing node that has been targeted and assigned to a variable.

#### Answer:
`pNode.insertBefore(newOne, existing.nextSibling);`

#### Question:
1. Create an <a> node.
2. Make it link to "bees.com".
3. Insert it before a node represented by a variable of your choosing, under a parent represented by a variable of your choosing.

#### Answer:
{% highlight javascript %}
var newE = document.createElement("a");
newE.setAttribute("href", "http://www.bees.com");
parentElement.insertBefore(newE, existingE);
{% endhighlight %}

#### Question:
1. Create a paragraph node.
2. Create a text node with content of your choosing.
3. Add it to the paragraph node.
4. Insert it before a node represented by a variable of your choosing, under a parent represented by a variable of your choosing.

#### Answer:
{% highlight javascript %}
var newP = document.createElement("p");
var newT = document.createTextNode("Hello world");
newP.appendChild(newT);
parentElement.insertBefore(newP, existingE);
{% endhighlight %}
