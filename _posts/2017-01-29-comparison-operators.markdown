---
layout: posts
title:  "Comparison operators"
tags: Javascript
---

#### Question:
`===`, `!==`, `>`, and `<=` are ________ operators.

#### Answer:
comparison.

#### Question:
What is the comparison operator for is not equal to?

#### Answer:
`!==`

#### Question:
What is the comparison operator for is greater than?

#### Answer:
`>`

#### Question:
What is the comparison operator for is less than or equal to?

#### Answer:
`<=`

#### Question:
Code the first line of an if statement that tests whether one variable is unequal to another.

#### Answer:
{% highlight javascript %}
	if (a !== b) {
{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether a variable has a different value from a particular string.

#### Answer:
{% highlight javascript %}
	if (gender !== "female") {
{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether a variable is less than a particular number.

#### Answer:
{% highlight javascript %}
	if (a < 5) {
{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether the value represented by a variable is greater than or equal to the value represented by another variable.

#### Answer:
{% highlight javascript %}
	if (a >= b) {
{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether a string is unequal to the value represented by a particular variable.

#### Answer:
{% highlight javascript %}
	if ("Mexico" !== countryOfOrigin) {
{% endhighlight %}

#### Question:
Live coding exercise:
1) Code an if statement that tests whether a number is unequal to a different number.
2) If the condition is true (it will be), display a congratulations alert.

#### Answer:
{% highlight javascript %}
	if (5 !== 4) {
	  alert("Congrats");
	}
{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a prompt asking for your first name.
2) Code an if statement that tests whether the name you entered is unequal to another name.
3) If the condition is true (it will be), display an alert that says "No match"

#### Answer:
{% highlight javascript %}
	var firstName = prompt ("first name");
	if (firstName !== "Sam") {
	  alert("No match");
	}
{% endhighlight %}