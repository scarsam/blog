---
layout: posts
title:  "The DOM: Counting elements"
tags: Javascript
---

#### Question:
Fill in the blank to make a collection of the nodes one level below the node represented by `pNode`.
`var nodeList = pNode.______;`

#### Answer:
`var nodeList = pNode.childNodes`

#### Question:
If the children of the paragraph are assigned to `kids`, what is the value of `kids.length`? (Answer with a numeral.)
`<p>This is <em>very</em> important!</p>`

#### Answer:
3—2 text nodes plus the <em> element

#### Question:
Fill in the blank. In the markup, document.getElementById("p1").childNodes[1].
nodeName is "_________"
`<p id="p1">This is <em>very</em> important!</p>`

#### Answer:
EM

#### Question:
Fill in the blank. In the markup, document.getElementById("p1").childNodes[1].
firstChild.nodeValue is "_________"
`<p id = "p1">This is <em>very</em> important!</p>`

#### Answer:
very

#### Question:
Make a collection of nodes one level down from an element represented by the variable `tDiv`. Assign the collection to a variable, `list`, which hasn't been declared beforehand.

#### Answer:
`var list = tDiv.childNodes;`

#### Question:
In a single statement, make a collection of nodes one level down from an element with the id "p3". Assign the collection to a variable, list, which hasn't been declared beforehand.

#### Answer:
`var list = document.getElementById("p3").childNodes;`

#### Question:
Make a collection of the nodes one level down from the html level. Assign the collection to a variable, list, which hasn't been declared beforehand.

#### Answer:
`var list = document.childNodes[0].childNodes;`

#### Question:
In a single statement, assign the number of child nodes of an element represented by the variable e to the variable numKids, which hasn't been declared beforehand.

#### Answer:
`var numKids = e.childNodes.length;`

#### Question:
Code the first line of an if statement that tests whether an element with the id "p3" has any child nodes by testing whether it has a first child node.

#### Answer:
`if (document.getElementById("p3").childNodes[0]) { `
