---
layout: posts
title:  "Testing sets of conditions"
tags: Javascript
---

#### Question:
Type the operator that means and.

#### Answer:
`&&`

#### Question:
Type the operator that means or.

#### Answer:
`||`

#### Question:
When both sides of an operator have to be true to pass the test, what operator is it? Type it.

#### Answer:
`&&`

#### Question:
Code the first line of an if statement that tests whether both are true: a first variable equals a second variable and also equals a third variable.

#### Answer:
{% highlight javascript %}

if (a === b && a === c) {

{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether either is true: a variable is less than or equal to a particular number or whether that same variable is greater than or equal to a second number.

#### Answer:
{% highlight javascript %}

if (a <= 7 || a >= 9) {

{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether (1) name is either "Ace" or "Bud" and (2) age is greater than 60.

#### Answer:
{% highlight javascript %}

if ((name === "Ace" || name === "Bud") && age > 60) {

{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether (1) name is "Ace" and age is greater than 60 or (2) name is "Bud".

#### Answer:
{% highlight javascript %}

if ((name === "Ace" && age > 60) || name === "Bud") {

{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether (1) name is "Ace" and age is greater than 60 or (2) name is "Bud" or age is under 6.

#### Answer:
{% highlight javascript %}

if ((name === "Ace" && age > 60) || (name === "Bud" || age < 6)) {
  
{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare two variables and assign them number values.
2) If the first variable is less than the second variable or greater than the second variable, display an alert.

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

var a = "Sam";
var b = "Ojling";
var firstName = prompt("First name?");
var lastName = prompt("Last name?");
if (firstName === a && lastName === b) {
  alert("Hello " + a + " " + b);
}

{% endhighlight %}