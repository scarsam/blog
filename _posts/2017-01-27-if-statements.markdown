---
layout: posts
title:  "if statements"
tags: Javascript
---

#### Question:
What are the first 4 characters of an if statement?

#### Answer:
`if (`

#### Question:
What character ends the first line of an if statement?

#### Answer:
`{`

#### Question:
What is the last line of an if statement?

#### Answer:
`}`

#### Question:
`if (city = "Las Vegas") {`
In the above statement, what character is incorrect?

#### Answer:
`=` should be `===`.

#### Question:
Code the first line of an if statement that tests whether one variable has the same value as another.

#### Answer:
{% highlight javascript %}
	if (a === b) {
{% endhighlight %}

#### Question:
Code the first line of an if statement that tests whether a variable has the value of a particular string.

#### Answer:
{% highlight javascript %}
	if (hello === "dance") {
{% endhighlight %}

#### Question:
This is the first line of an if statement:
`if (x === y) {`
Complete the statement. If the condition is true, display a box that asks the user a question. Assign the answer to a variable that hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}
	if (x === y) {
	  var answer = prompt("What is z?");
	}
{% endhighlight %}

#### Question:
Code an if statement that tests whether pCode is "10010". If so, assign to the variable city the string "New York". city has already been declared.

#### Answer:
{% highlight javascript %}
	if (pCode === "10010") {
	  city = "New York";
	} 
{% endhighlight %}

#### Question:
Code an if statement. Test whether a variable has a particular numerical value. If so, assign a new value to that variable, as in x = 1;

#### Answer:
{% highlight javascript %}
	if (pets === 1) {
	  pets = 2;
	} 
{% endhighlight %}

#### Question:
Live coding exercise:
1) Code an if statement that tests whether a number equals itself.
2) If the condition is true (it will be), display a congratulations alert.

#### Answer:
{% highlight javascript %}
	if (1 === 1) {
	  alert("Congrats");
	}
{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a prompt asking for your first name.
2) Code an if statement that tests whether the name you entered equals your name.
3) If the condition is true (it will be), display an alert that greets you by name.

#### Answer:
{% highlight javascript %}
	var name = prompt("first name?");
	if (name === "Sam") {
	  alert("Hello " + name);
	}
{% endhighlight %}