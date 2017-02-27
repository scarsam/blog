---
layout: posts
title:  "Functions"
tags: Javascript
---

#### Question:
In one word, what is a block of code that executes whenever you invoke its name?

#### Answer:
function

#### Question:
Any name that is legal for a _________ is legal for a function.

#### Answer:
variable

#### Question:
Write a function call that uses just 4 characters. Name it anything you like, within the limitation that the whole statement is just 4 characters.

#### Answer:
f();

#### Question:
This is the first line of the function code. Write the statement that calls it.
`function doSomething() {`

#### Answer:
doSomething();

#### Question:
Code the first line of a function named for Johnny Appleseed's favorite fruit.

#### Answer:
`function apple() {`

#### Question:
Code a function named say that displays an alert with your first name as the message.

#### Answer:
{% highlight javascript %}

function say() {
  alert("Sam");
}

{% endhighlight %}

#### Question:
Code a function that concatenates string1 and string2 and assigns the result to a variable that hasn't been declared beforehand. (For the sake of practice, I'm asking you to violate a good-coding rule here, which you'll learn about in Chapter 38. If you're charged with a coding crime, I'll testify to your innocence.)

#### Answer:
{% highlight javascript %}

function concat() {
  var strings = string1 + string2;
}
{% endhighlight %}

#### Question:
What are the 4 missing characters, including a space?
`function doSomething`

#### Answer:
`function doSomething() {`

#### Question:
Code a function that calls itself.

#### Answer:
{% highlight javascript %}

function hello() {
  hello();
}
{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a function that displays an alert, "Hello world." Call the function. If nothing happens, there is an error in your code.

#### Answer:
{% highlight javascript %}

function helloWorld() {
  alert("Hello world");
}
helloWorld();

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create a Date object for the current date and time.
2) Extract the year.
3) Reset the Date object a century back.
4) Display the date Object in an alert.

#### Answer:
{% highlight javascript %}

var d = new Date();
var year = d.getFullYear();
d.setFullYear(year - 100);
alert(d);

{% endhighlight %}
