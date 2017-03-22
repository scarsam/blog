---
layout: posts
title:  "Objects: Methods"
tags: Javascript
---

#### Question:
A function that's attached to an object is known as a _______.

#### Answer:
`method`

#### Question:
Call the object contract's method printIt, with the argument "IBM"

#### Answer:
`contract.printIt("IBM");`

#### Question:
The highlighted code can be replaced by ______.
{% highlight javascript %}
var topic11 = {
  title: "Dancing",
  showIt: function() {
    alert("The topic is" + topic11.title);
  }
};
{% endhighlight %}

#### Answer:
`this`

#### Question:
Type what's missing.
{% highlight javascript %}
var topic11 = {
  title: "Dancing",
  namePlace: function() {
    this.venue = "Elaine's";
  }
  showIt: function() {
    alert("Meet at " + this.venue);
  }
};
{% endhighlight %}

#### Answer:
, after the first function.

#### Question:
Call a method of an object, passing a whole number to it.

#### Answer:
`offer.timeLimit(30);`

#### Question:
Code the first line of a method with 2 parameters.

#### Answer:
`timeLimit: function(minimum, maximum) {`

#### Question:
Code an object that has a single method that doesn't do anything.

#### Answer:
{% highlight javascript %}
var x = {
  dance: function() {
  }
};
{% endhighlight %}

#### Question:
Code an object that has a single method that displays an alert with a text message.

#### Answer:
{% highlight javascript %}
var x = {
  msg: function() {
    alert("this is an alert");
  }
};
{% endhighlight %}

#### Question:
Code an object that has one property, a number, and one method. The method multiplies the property by 10 and sends the result back to the calling code. Don't refer to the object by name in the method.

#### Answer:
{% highlight javascript %}
var numObj = {
  magicNum: 100,
  multiplyBy10: function() {
    return this.magicNum * 10;
  }
};
{% endhighlight %}

#### Question:
Define an object with one property and one method. The method displays the value of the property in an alert. Call the method.

#### Answer:
{% highlight javascript %}
var x = {
  msg: "This is an alert",
  display: function() {
    alert(this.msg);
  }
};
x.display();
{% endhighlight %}

#### Question:
Code an object with one method. The method has one parameter, a whole number. The method tests whether the number is 10 and displays an alert with the results of the test. Call the method, specifying a whole number as the argument.

#### Answer:
{% highlight javascript %}
var niceObj = {
  displayIt: function(num) {
    if (num === 10) {
      alert("It's 10.");
    }
    else {
      alert("It isn't 10.");
    }
  }
};
niceObj.displayIt(9); 
{% endhighlight %}
