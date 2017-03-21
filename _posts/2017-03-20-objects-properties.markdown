---
layout: posts
title:  "Objects: Properties"
tags: Javascript
---

#### Question:
Delete a property.

#### Answer:
`delete dance.size;`

#### Question:
Change the value of a property. Make it a number.

#### Answer:
`shoe.size = 15;`

#### Question:
Assign two strings to a property that's an array.

#### Answer:
`greeting.phrase = ["hi", "hello"];`

#### Question:
Create an object with no properties.

#### Answer:
`var plan1 = {};`

#### Question:
Assign a value represented by a variable to a property.

#### Answer:
`shoe.size = shoeSize;`

#### Question:
Create 2 new properties for the same object. The first property is a number. The second property is a Boolean.

#### Answer:
{% highlight javascript %}
shoe.size = 15;
shoe.fits = true;
{% endhighlight %}

#### Question:
Assign a property of one object to the same property of another object.

#### Answer:
`shoe.size = danceshoe.size;`

#### Question:
Code the first line of an `if` statement that tests whether the object `product` has the property `qty`.

#### Answer:
`if ("qty" in product) {`

#### Question:
Code the first line of an if statement that tests whether there is a 10th element in a property that is an array. Don't do it by testing for the length of the array.

#### Answer:
`if (product.colors[9]) { `

#### Question:
Change the name to "Slinky". Then display the name in an alert. Don't change any of my code. Don't copy and paste the answer. It may not work.
{% highlight javascript %}
var productB = {
  name: "Rubber duck",
  units: 11
};
{% endhighlight %}

#### Answer:
{% highlight javascript %}
var productB = {
  name: "Rubber duck",
  units: 11
};
productB.name = "Slinky";
alert(productB.name);
{% endhighlight %}

#### Question:
In a single statement, display an alert that shows the value you get if you ask whether the object `phantom` has a property called `substance`. Don't change any of my code. Don't copy and paste the answer. It may not work.
`var phantom = {};`

#### Answer:
{% highlight javascript %}
var phantom = {};
alert("substance" in phantom);
{% endhighlight %}
