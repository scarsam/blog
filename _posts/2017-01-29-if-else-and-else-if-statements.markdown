---
layout: posts
title:  "if...else and else if statements"
tags: Javascript
---

#### Question:
What keyword specifies an action when all tests above have failed?

#### Answer:
`else`

#### Question:
What are the keywords that test for a condition when all tests above it have failed?

#### Answer:
`else if`

#### Question:
In one word, what type of statement is formatted the same way as else and else if?

#### Answer:
`if`

#### Question:
What is the last line of an else block?

#### Answer:
`}`

#### Question:
Code a block, that, if tests above it fail, checks whether one variable doesn't equal another and, if so, displays a prompt that assigns the user's response to a variable that has been declared beforehand.

#### Answer:
{% highlight javascript %}

else if (a !== b) {
	response = prompt("How many dogs do you own?");
}

{% endhighlight %}

#### Question:
Code an if statement that tests whether the value represented by a variable is greater than or equal to the value represented by another variable. If so, display an alert. If not, display a different alert.

#### Answer:
{% highlight javascript %}

if (a >= b) {
  alert("OK");
}
else {
  alert("Not OK");
} 

{% endhighlight %}

#### Question:
Code an if statement that tests whether the value represented by a variable is less than the value represented by another variable. If so, display an alert. If not, test whether the value represented by the first variable is greater than the value represented by the second variable. If so, display a different alert.

#### Answer:
{% highlight javascript %}

if (var < var2) {
  alert("First");
}
else if (var > var2) {
  alert("Second");
}

{% endhighlight %}

#### Question:
This is the if statement that begins the code.

if (a === 10) {
  alert("a is 10");
}

If a isn't 10, display an alert that says "a is " followed by the value of a.

#### Answer:
{% highlight javascript %}

else {
  alert("a is " + a);
} 

{% endhighlight %}

#### Question:
Live coding exercise:
1) Prompt the user to enter a city.
2) If the city is Akron, display an alert acknowledging it.
3) If not, display an alert acknowledging it isn't Akron.

#### Answer:
{% highlight javascript %}

var city = prompt("What city?");
if (city === "Akron") {
  alert("The city is Akron");
else {
  alert("City is not Akron");
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Prompt the user to enter a city.
2) If the city is Akron, display an alert acknowledging it.
3) If not, check to see if it's Buffalo.
4) If it is, display an alert acknowledging it's Buffalo.
5) Otherwise, display a different alert.

#### Answer:
{% highlight javascript %}

var city = prompt("Enter a city");
if (city === "Akron") {
  alert("The city is Akron");
else if (city === "Buffalo");
  alert("It's Buffalo");
}
else {
  alert("Other");
}

{% endhighlight %}