---
layout: posts
title:  "Math Expressions: unfamiliar operators"
tags: Javascript
---

#### Question:
What is the difference between having increase value of both variables with `++` sign.

#### Answer:
When the `++` comes afterward..
`x = y++;`
incrementing happens after the assignment, so the first variable gets left out ouf the increase.

When the `++` comes before..
incrementing happens before the assignment, so the first variable shares the wealth.

#### Question:
Code a short form of `x = x + 1;` Use either of the two legal expressions.

#### Answer:
{% highlight javascript %}
	x++;
{% endhighlight %}

#### Question:
If x has a value of 100, what is the fastest way to reduce it to 99 with a math expression? Use either of the two legal expressions.

#### Answer:
{% highlight javascript %}
	x--;
{% endhighlight %}

#### Question:
`var x = 50;`
`var y = x++;`
What is the value of `y`?

#### Answer:
The value of `y` is `50` because the `++` was placed afterward which won't affect the outcome of the value in varable `y`. 

#### Question:
`var x = 50;`
`var y = --x;`
What is the value of `y`?

#### Answer:
The value of `y` is `49` because the `--` was placed before the assignment which will affect the outcome of the value in varable `y`. 

#### Question:
Using minimal code, decrement `x`. Use either of the two legal expressions.

#### Answer:
{% highlight javascript %}
	x--;
{% endhighlight %}

#### Question:
What is the long version of x++?

#### Answer:
{% highlight javascript %}
	x = x + 1;
{% endhighlight %}

#### Question:
In a single statement subtract 1 from a variable and assign the new value to another variable, which hasn't been declared beforehand. Both variables wind up with the same value.

#### Answer:
{% highlight javascript %}
	var test = --fest;
{% endhighlight %}

#### Question:
In a single statement add 1 to a variable and assign its original value to another variable, which hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}
	var test = fest++;
{% endhighlight %}

#### Question:
Increment a variable. Use either of the two legal expressions. In a second statement, display its new value in an alert.

#### Answer:
{% highlight javascript %}
	var test++;
	alert(test);
{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a number value to a variable.
2 )Increment the variable using minimal code. Use either of the two legal expressions.
3) Display the new value in an alert.

#### Answer:
{% highlight javascript %}
	var test = 10;
	test++;
	alert(test);
{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a number value to a variable.
2) Increment the variable using minimal code while assigning its incremented value to a second variable. Both variables wind up with the same value.
3) Display the value of the second variable in an alert.

#### Answer:
{% highlight javascript %}
	var test = 10;
	var fest = ++test;
	alert(fest);
{% endhighlight %}