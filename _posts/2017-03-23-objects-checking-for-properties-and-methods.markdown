---
layout: posts
title:  "Objects: Checking for properties and methods"
tags: Javascript
---

#### Question:
The statement checks to see whether the object thing has a property called color. Fill in the blank.
`var isPropertyOf = "color" ____ thing;`

#### Answer:
`var isPropertyOf = "color" in thing;`

#### Question:
If the object has such a property, what is the value of `isPropertyOf`?
`var isPropertyOf = "color" in thing;`

#### Answer:
`true`

#### Question:
If the object has a method `doesSomething`, what is the value of `isPropertyOf`?
`var isPropertyOf = "doesSomething" in thing;`

#### Answer:
`true`

#### Question:
What 2 characters are missing?
`var isPropertyOf = size in thing;`

#### Answer:
Quotation marks `var isPropertyOf = "size" in thing;`

#### Question:
Code a statement that tests whether the object a has a property b, and assign the result to the variable c, which hasn't been declared beforehand.

#### Answer:
`var c = "b" in a;`

#### Question:
Code the first line of an if statement that checks to see if an object has a particular property.

#### Answer:
`if ("a" in b) {`

#### Question:
Code the first line of a for loop that cycles through all the properties of an object.

#### Answer:
`for (var x in prop) {`

#### Question:
Code the first line of an if statement that tests whether the property "color" was explicitly assigned to an object as opposed to inherited.

#### Answer:
`if (plan2.hasOwnProperty("color")) {`

#### Question:
Declare an empty array. Fill the array with all the properties of an object.

#### Answer:
{% highlight javascript %}
var allProps = [];
for (var item in modelX) {
  allProps.push(item);
}
{% endhighlight %}

#### Question:
1) Code an alert that confirms the object has such a property.
{% highlight javascript %}
var anObject = {
  color: "blue"
}
{% endhighlight %}

#### Answer:
{% highlight javascript %}
var anObject = {
  color: "blue"
}
alert("color" in anObject);
{% endhighlight %}

#### Question:
1) Code an alert that confirms the object has such a property which was assigned explicitly to the object rather than being inherited from a prototype.
{% highlight javascript %}
var anObject = {
  color: "blue"
}
{% endhighlight %}

#### Answer:
{% highlight javascript %}
var anObject = {
  color: "blue"
}
alert(anObject.hasOwnProperty("color"));
{% endhighlight %}
