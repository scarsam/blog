---
layout: posts
title:  "Objects: Constructors"
tags: Javascript
---

#### Question:
A function that creates objects and their properties is known as a _______ function.

#### Answer:
`constructor`

#### Question:
Read the following code and tell me what the name of the object will be.
`var sham = new Scam(50000);`

#### Answer:
`sham`

#### Question:
There's an incorrect word in this statement. The correct word is ______.
`var sham = new scam();`

#### Answer:
Scam

#### Question:
In a constructor function, what is the keyword that is replaced by the object name when the function executes?

#### Answer:
`this`

#### Question:
Create an object by calling a constructor function. Give the object one property, a number. Don't forget to capitalize the function name.

#### Answer:
`var x = new Number(10);`

#### Question:
Code the first line of a constructor function that creates an object with one property. Don't forget to capitalize the function name.

#### Answer:
`function MakeObject(price) {`

#### Question:
Create an object using a constructor function. The argument is the property of another object.

#### Answer:
`var pkg99 = new Package(pkg0.width);`

#### Question:
Code a constructor function that creates objects with 2 properties.

#### Answer:
{% highlight javascript %}
function City(altitude, population) {
  this.altitude = altitude;
  this.population = population;
}
{% endhighlight %}

#### Question:
Code a constructor function that creates objects with 2 properties. Name the parameters and the property names differently.

#### Answer:
{% highlight javascript %}
function Facility(param1, param2) {
  this.location = param1;
  this.size = param2;
}
{% endhighlight %}

#### Question:
On the four lines above the function call, code the constructor function that creates the object and its properties. The parameters are color and gender.
{% highlight javascript %}
var cat10 = new Cat("white", "female");
alert("The cat is a "+cat10.color + " " + cat10.gender);
{% endhighlight %}

#### Answer:
{% highlight javascript %}
function Cat(color, gender) {
  this.color = color;
  this.gender = gender;
}
var cat10 = new Cat("white", "female");
alert("The cat is a "+cat10.color+" "+cat10.gender);
{% endhighlight %}

#### Question:
1) Code a constructor function that creates an object with one property.
2) Call the function to create an object.
3) Display the object's property in an alert.

#### Answer:
{% highlight javascript %}
function Hello(greeting) {
  this.greeting = greeting;
};
var msg = new Hello("Hello");
alert(msg.greeting);
{% endhighlight %}
