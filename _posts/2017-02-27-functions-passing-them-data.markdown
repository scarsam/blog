---
layout: posts
title:  "Functions: passing them data"
tags: Javascript
---

#### Question:
The variables in a function definition that catch the data passed to them by the calling code are called _________.

#### Answer:
parameters

#### Question:
When there are multiple arguments and parameters, type the character that separates the individual items in the list

#### Answer:
,

#### Question:
The rules for naming parameters are the same as the rules for naming ______.

#### Answer:
variables

#### Question:
When there are multiple arguments and parameters, the arguments and parameters are matched up by their (1 word) _______.

#### Answer:
order

#### Question:
Code a function call that takes a variable, a string, and a number as arguments.

#### Answer:
`makeAddress(city, "Texas", 24);`

#### Question:
Code the first line of a function that has 2 parameters.

#### Answer:
function hello(param1, param2) {

#### Question:
Code a function that has 2 parameters. Concatenate them and assign the result to a variable that hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}

function hello(param1, param2) {
  var dance = param1 + param2;
}

{% endhighlight %}

#### Question:
The function call is:
`calc("Funds received", 500000);`
Code the first line of the function.

#### Answer:
function calc(param1, param2) {

#### Question:
Code a function that has three parameters. Multiply them and assign them to a variable that hasn't been declared yet.

#### Answer:
{% highlight javascript %}

function hello(param1, param2, param3) {
  var total = param1 * param2 * param3;
}

{% endhighlight %}

#### Question:
Live coding exercise:
I've coded the call to the function that displays the alert. Code the function. Leave my code as-is. Add your code below it.
{% highlight javascript %}

var part1 = "The medium ";
var part2 = "is the message.";
displayIdiom(part1, part2);

{% endhighlight %}


#### Answer:
{% highlight javascript %}

var part1 = "The medium ";
var part2 = "is the message.";
displayIdiom(part1, part2);
function displayIdiom() {
  alert(part1 + part2);
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a function with 2 number parameters. Sum them and assign the sum to a variable. The function displays an alert concatenating "The sum is " with the variable. Code the function call.

#### Answer:
{% highlight javascript %}

function sum(num1, num2) {
  var total = num1 + num2;
  alert("The sum is " + total);
}
sum(20, 20);

{% endhighlight %}
