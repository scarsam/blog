---
layout: posts
title:  "Objects: Prototypes"
tags: Javascript
---

#### Question:
What is the keyword that allows all objects created by a particular constructor to share the same property or function?

#### Answer:
`prototype`

#### Question:
This is the first line of a prototype statement that creates a prototype method for the constructor `MakeObj`. Fill in the blank.
`MakeObj.________.calcTax = function(price) {`

#### Answer:
`MakeObj.prototype.calcTax = function(price) {`

#### Question:
This is the first line of a prototype statement that creates a prototype method for the constructor `Product`. Fill in the blank.
`______.prototype.selectPkg = function(dimensions, weight) {`

#### Answer:
`Product.prototype.selectPkg = function(dimensions, weight) {`

#### Question:
This is the first line of a prototype statement that creates a prototype method for the constructor `Product`. The method has no parameters. Fill in the blank.
`Product.prototype.totalCosts = _____________`

#### Answer:
`Product.prototype.totalCosts = function() {`

#### Question:
Code a statement that creates a prototype number property.

#### Answer:
`Shoe.prototype.size = 10;`

#### Question:
There is a prototype property, `caseQty`, for the constructor `Product`. Its value is 12. Make an exception for `product332`. Its `caseQty` is 6.

#### Answer:
`product332.caseQty = 6;`

#### Question:
Code a method prototype that has no parameters and does nothing.

#### Answer:
{% highlight javascript %}
MakeObj.prototype.doNothing = function() {
};
{% endhighlight %}

#### Question:
Code a method prototype that displays a message. The message text is passed to the method by the statement that calls the method, not by the constructor.

#### Answer:
{% highlight javascript %}
Message.prototype.txt = function(copy) {
  alert(copy);
};
{% endhighlight %}

#### Question:
Code a method prototype that displays a message. The message text is passed to the method by the constructor, not the statement that calls the method.

#### Answer:
{% highlight javascript %}
Message.prototype.txt = function() {
  alert(this.txt);
};
{% endhighlight %}

#### Question:
1) Code a prototype property for the constructor function I created on the first line.
2) My third line creates a new object using the constructor. Display the value of its prototype property in an alert.

#### Answer:
{% highlight javascript %}
function MakeObj() {
}
var thing = new MakeObj();
MakeObj.prototype.color = "white";
alert(thing.color);
{% endhighlight %}

#### Question:
1) Code a constructor function that creates an object with one property.
2) Call the function to create an object, passing a value for the property.
3) Code a prototype method that displays the object's property.
4) Call the method.

#### Answer:
{% highlight javascript %}
function OneProp(color) {
  this.color = color;
}
var colorObj = new OneProp("white");
OneProp.prototype.displayColor = function() {
  alert(this.color);
};
colorObj.displayColor();
{% endhighlight %}
