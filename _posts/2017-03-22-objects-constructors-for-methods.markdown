---
layout: posts
title:  "Objects: Constructors for methods"
tags: Javascript
---

#### Question:
When you see this line of code, you know it's part of a _______ function.
`this.doSomething = function() {`

#### Answer:
`constructor`

#### Question:
Rewrite this to adapt it for a constructor function.
`doSomething: function() {`

#### Answer:
`this.doSomething = function() {`

#### Question:
Calling a constructor function, `MakeObj`, create an object, `simpleObj`. The call has no arguments.

#### Answer:
`var simpleObj = new MakeObj();`
A constructor doesn't necessarily need any values to be passed in order to create an object with no properties and one method. A method can and often is created without taking any values passed from the code that calls the constructor. Of course, this would be a trivial use for a constructor, since all objects it creates would be identical.

#### Question:
The method definition in a constructor has three features that a one-off literal definition doesn't have. Two of them are = in the definition and ; after the closing curly bracket. What is the third feature? (5 characters)

#### Answer:
`this`

#### Question:
Rewrite this line so it'll work in a constructor function.
`addTaxTo: function(price) {`

#### Answer:
`this.addTaxTo = function(price) {`

#### Question:
Code the first line of a method without parameters in a constructor.

#### Answer:
`this.addTaxTo = function() {`

#### Question:
Code the first line of a method with 2 parameters in a constructor.

#### Answer:
`this.shoe = function(size, color) {`

#### Question:
Code a constructor function that creates a method that does nothing.

#### Answer:
{% highlight javascript %}
function WhyBother() {
  this.doNothing = function() {
  };
}
{% endhighlight %}

#### Question:
Code a constructor function that creates a property and a method that displays the property in an alert.

#### Answer:
{% highlight javascript %}
function SaysSomething(message) {
  this.message = message;
  this.sayIt = function() {
    alert(this.message);
  };
}
{% endhighlight %}

#### Question:
1) Code a constructor function that creates a property and a method that displays the property in an alert.
2) Use the constructor to create a new object.
3) Call the method.

#### Answer:
{% highlight javascript %}
function X(msg) {
  this.msg = msg;
  this.sayIt = function() {
    alert(this.msg);
  };
}
var createObj = new X("dance");
createObj.sayIt();
{% endhighlight %}

#### Question:
1) Code a constructor function that creates an object with no properties and one method that creates an alert.
2) Call the function to create an object.
3) Call the object's method, with the message text as an argument.

#### Answer:
{% highlight javascript %}
function SaysSomething() {
  this.sayIt = function(message) {
    alert(message);
  };
}
var myObj = new SaysSomething();
myObj.sayIt("Hello world!");
{% endhighlight %}
