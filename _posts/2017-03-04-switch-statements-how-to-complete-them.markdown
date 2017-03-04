---
layout: posts
title:  "switch statements: how to complete them"
tags: Javascript
---

#### Question:
The next line begins with what 2 characters? Type them.

{% highlight javascript %}

switch(varToTest) {
case "Cleveland" :

{% endhighlight %}

#### Answer:
2 spaces—to indent the statement that executes.

#### Question:
In a switch statement, if a condition is met, some code executes. Think of the line of code that precedes the code that executes. What is the first word of that line?

#### Answer:
case

#### Question:
What statement keeps all the statements below the true case from executing?

#### Answer:
`break;`

#### Question:
Type the last line of a switch statement.

#### Answer:
}

#### Question:
Code the catch-all clause that specifies what happens if none of the above cases is true.

#### Answer:
`default :`

#### Question:
Code the first 4 lines of a switch statement that tests to see if a variable is assigned one number or another. If the first test passes, a variable (already declared) is assigned a Boolean value.

#### Answer:
{% highlight javascript %}

switch(num) {
case 10 :
  correct = true;
  break;

{% endhighlight %}

#### Question:
Code 2 lines of a switch statement that specify that a variable (already declared) is assigned a number if no specific cases are true.

#### Answer:
{% highlight javascript %}

default :
  num = 1;

{% endhighlight %}

#### Question:
When the statement finishes executing, what is the value of `performers`?
{% highlight javascript %}

var group = "duo";
switch(group) {
case "solo" :
  performers = 1;
case "duo" :
  performers = 2;
case "trio" :
  performers = 3;
}

{% endhighlight %}

#### Answer:
The answer is 3. Because there are no break statements to prevent execution from continuing to the bottom, two statements execute, the second one inappropriately. First, the value 2 is assigned to the variable when the second case is found to be true, but then the runaway code changes the value to 3 on line 8.

#### Question:
Code the rest of this switch statement, assigning "none" to the variable if all tests above fail. Be sure to close the switch statement with a bracket.
{% highlight javascript %}

var meds;
switch(illness) {
case "cold" :
  meds = "aspirin";
  break;
case "malaria" :
  meds = "quinine";
  break;

{% endhighlight %}

#### Answer:
{% highlight javascript %}

var meds;
switch(illness) {
case "cold" :
  meds = "aspirin";
  break;
case "malaria" :
  meds = "quinine";
  break;
default :
  meds = "none";
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare a variable and assign it a value. Code a single-case switch statement that tests whether the variable has been assigned the value. If so, alert "Assigned"

#### Answer:
{% highlight javascript %}

var number = 5
switch(number) {
case 5 :
  alert("Assigned");
  break;
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a switch statement that assigns a string to message. If today is Sunday (0) or Saturday (6), the message is "Weekend!" Otherwise, the message is "Weekday." On the last line, code an alert that displays the message.(Leave my code as-is and add your code to it.)

{% highlight javascript %}

var now = new Date();
var today = now.getDay();
var message;

{% endhighlight %}

#### Answer:
{% highlight javascript %}

var now = new Date();
var today = now.getDay();
var message;
switch(today) {
case 0 :
  message = "Weekend!";
  break;
case 6 :
  message = "Weekend!";
  break;
default :
  message = "Weekday";
}
alert(message);​

{% endhighlight %}
