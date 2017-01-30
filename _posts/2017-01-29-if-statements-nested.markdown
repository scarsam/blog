---
layout: posts
title:  "if statements nested"
tags: Javascript
---

#### Question:
An alternative to using `&&` to test multiple conditions in a single if statement is ______ ifs.

#### Answer:
nested ifs

#### Question:
You communicate the nesting to JavaScript with the placement of what two characters? Don't type a space between them.

#### Answer:
`{}`

#### Question:
How do you make nested ifs readable? Answer with 1 lower-case verb.

#### Answer:
indent.

#### Question:
This is the first line of an if statement.
`if (a !== b) {`
Enter the first 6 characters of the next line, which is a second-level if.

#### Answer:
{% highlight javascript %}

	if else (

{% endhighlight %}
Make sure you indent.

#### Question:
if (a === 1) {
  if (c === "Max") {
    alert("OK");
  }
}
Code the first line of an if statement that avoids the nesting above by testing for multiple conditions.

#### Answer:
{% highlight javascript %}

if (a === 1 && c === "Max") {

{% endhighlight %}

#### Question:
Code nested if statements that test whether a first variable equals a particular number and whether a second variable equals another number. If so, display an alert message.

#### Answer:
{% highlight javascript %}

if (a === 0) {
  if (b === 1) {
    alert("OK");
  }
} 

{% endhighlight %}

#### Question:
Code nested if statements that test whether a first variable equals a second variable, whether a third variable doesn't equal a fourth variable, and whether a fifth variable is greater than a sixth variable. If all tests pass, assign a number value to a seventh variable, which hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}

if (a === b) {
  if (c !== d) {
    if (e > f) {
      var g = 1;
    } 
  }
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare two variables and assign them the same number value.
2) Test two conditions, using nested if statements. Test whether the first variable equals the second variable and also whether it is less than or equal to the second variable. If the test passes—and it will—display an alert message.

#### Answer:
{% highlight javascript %}

var a = 1;
var b = 1;
if (a === b) {
  if (a <= b) {
    alert("Test pass");
  }
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare 2 variables. Assign one of them your first name and the other one your last name.
2) Code 2 prompts, asking for your first and your last name.
3) Using nested if statements, test whether your answers match the two variables. If so, display an alert.

#### Answer:
{% highlight javascript %}

var a = 5;
var b = 10;
if (a < b || a > b) {
  alert("will show this");
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare 2 variables. Assign one of them your first name and the other one your last name.
2) Code 2 prompts, asking for your first and your last name.
3) If your answers match the two variables, display an alert.

#### Answer:
{% highlight javascript %}

var firstName = "Sam";
var lastName = "Ojling";
var inputFirstName = prompt("First name");
var inputLastName = prompt("Last name");
if (inputFirstName === "Sam") {
  if (inputLastName === "Ojling") {
    alert(inputFirstName + " " + inputLastName);
  }
}

{% endhighlight %}