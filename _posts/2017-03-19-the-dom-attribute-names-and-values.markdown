---
layout: posts
title:  "The DOM: Attribute names and values"
tags: Javascript
---

#### Question:
Fill in the blank to make a collection of attributes and assign it to `attList`.
`var attList = targetNode.___________;`

#### Answer:
`var attList = targetNode.attributes;`

#### Question:
Look at the following markup and the code that follows it, and tell me the value of `num`. (Answer with a numeral.)
{% highlight javascript %}
<p id="p1" class="regular" onClick="disappear();">

var num = document.getElementById("p1").
    attributes.length;
{% endhighlight %}

#### Answer:
3

#### Question:
Look at the following markup and the code that follows it, and tell me the value of `nam`. Include the quotation marks.
{% highlight javascript %}
<p id="p1" class="regular" onClick="disappear();">

var nam = document.getElementById("p1").
    attributes[2].nodeName;
{% endhighlight %}

#### Answer:
"onclick"

#### Question:
Look at the following markup and the code that follows it, and tell me the value of `val`. Include the quotation marks.
{% highlight javascript %}
<p id="p1" class="regular" onClick="disappear();">

var target = document.getElementById("p1");
var val = target.attributes[1].nodeValue;
{% endhighlight %}

#### Answer:
"regular"

#### Question:
In a single statement get a collection of the attributes of an element with an id of your choosing, and assign the collection to a variable of your choosing, which hasn't been declared beforehand.

#### Answer:
`var collection = document.getElementById("testID").attributes;`

#### Question:
Get the number of attributes of an element that has been assigned to a variable of your choosing, and assign the number to another variable of your choosing, which hasn't been declared beforehand.

#### Answer:
`var number = myVar.attributes.length;`

#### Question:
Get the name of the second attribute of an element that has been assigned to a variable of your choosing, and assign the name to another variable of your choosing, which hasn't been declared beforehand.

#### Answer:
`var myVar = test.attributes[1].nodeName;`

#### Question:
In a single statement, get the value of the first attribute of an element with an id of your choosing and assign it to a variable of your choosing, which hasn't been declared beforehand.

#### Answer:
`var val = document.getElementById("e1").attributes[0].nodeValue;`

#### Question:
Code the first line of an if statement that tests whether the second attribute of an element with the id "e1" is not class.

#### Answer:
`if (document.getElementById("e1").attributes[1].nodeName !== "class") {`
