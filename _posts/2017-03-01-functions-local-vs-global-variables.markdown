---
layout: posts
title:  "Functions: local vs. global variables"
tags: Javascript
---

#### Question:
A variable declared in the main code is a ______ variable.

#### Answer:
global variable

#### Question:
A variable declared in a function is a ________ variable.

#### Answer:
local variable

#### Question:
A parameter is a ________ variable.

#### Answer:
local variable

#### Question:
What is the name that differentiate local variable and global.

#### Answer:
Their scope

#### Question:
Code a statement that assigns the value returned by a function to a global variable.

#### Answer:
var hello = dance();

#### Question:
Code a function without parameters that does nothing but create two local variables.

#### Answer:
{% highlight javascript %}

function hello() {
  var dance;
  var hello2;
}

{% endhighlight %}

#### Question:
Code a statement that passes the value of a local variable to a global variable in the main code.

#### Answer:
`return total;`
The value of the local variable total is passed back to the calling statement via the return statement.

#### Question:
Code a statement that passes the values of two global variables to a function and anticipates that the function will return a value to be assigned to a new global variable. The global variable hasn't been declared beforehand.

#### Answer:
var hello = dance(hello2, hello3);

#### Question:
Code a function without parameters that creates two local variables and does nothing with them. Then it (unwisely) assigns the number 10 to a global variable that you've made up without a return statement.

#### Answer:
{% highlight javascript %}

function reckless() {
  var safeVariable1;
  var safeVariable2;
  unsafeVariable = 10;
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Insert the missing line of code. Leave my code as-is except for your additional line of code. The correct code displays an alert with the message "Abraham Lincoln."

{% highlight javascript %}

function makeMessage(part1, part2) {
  var message = part1 + part2;

}

var firstName = "Abraham ";
var lastName = "Lincoln";
alert(makeMessage(firstName, lastName));

{% endhighlight %}


#### Answer:
{% highlight javascript %}

function makeMessage(part1, part2) {
  var message = part1 + part2;
  return message;
}

var firstName = "Abraham ";
var lastName = "Lincoln";
alert(makeMessage(firstName, lastName));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Insert the missing line of code. Leave my code as-is except for your additional line of code. The correct code displays an alert showing the total of the three numbers.

{% highlight javascript %}

function calcTotal(num1, num2, num3) {

  return total;
}

alert(calcTotal(12, 24, 48));

{% endhighlight %}

#### Answer:
{% highlight javascript %}

function calcTotal(num1, num2, num3) {
  var total = num1 + num2 + num3;
  return total;
}

alert(calcTotal(12, 24, 48));

{% endhighlight %}
