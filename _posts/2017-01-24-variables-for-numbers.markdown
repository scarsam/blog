---
layout: posts
title:  "Variables for Numbers"
tags: Javascript
---

#### Question:
You can assign a string to a variable. You can also assign a ______.

#### Answer:
Number

#### Question:
If a number is enclosed in quotes, it's a ______.

#### Answer:
String

#### Question:
What kind of operation can be done on a number variable that, in one particular case, can't be done on a string variable? Answer with a 4-letter word.

#### Answer:
Math

#### Question:
What is the value of `orderTotal`?
{% highlight javascript %}
	var merchTotal = 100;
	var shippingCharge = 10;
	var orderTotal = merchTotal + shippingCharge;
{% endhighlight %}

#### Answer:
The answer is 100 + 10 = 10
`orderTotal = 10`

#### Question:
In a single statement declare a variable and assign a number to it. (You've learned only two rules for naming variables so far—no quotes and no initial number—so they're the only ones I'll hold you to.)

#### Answer:
{% highlight javascript %}
	var exercise = 19;
{% endhighlight %}

#### Question:
In a single statement declare a variable and assign to it the sum of 2 other variables. (You've learned only two rules for naming variables so far, so they're the only ones I'll hold you to.)

#### Answer:
{% highlight javascript %}
	var exercise = test + test2;
{% endhighlight %}

#### Question:
Rewrite this statement so the variable can be used in a math operation.
`var num = "9";`

#### Answer:
Quotation marks is making the variabe a string which can't be used for math.
{% highlight javascript %}
	var num = 9;
{% endhighlight %}

#### Question:
Assign the sum of 2 numbers to a variable, which hasn't been declared beforehand. (You've learned only two rules for naming variables so far, so they're the only ones I'll hold you to.)

#### Answer:
{% highlight javascript %}
	var exercise = 2 + 2; 
{% endhighlight %}

#### Question:
In one statement declare a variable. In a second statement assign it the sum of 2 numbers. (You've learned only two rules for naming variables so far, so they're the only ones I'll hold you to.)

#### Answer:
{% highlight javascript %}
	var exercise;
	exercise = 2 + 2;
{% endhighlight %}

#### Question:
In one statement declare a variable. In a second statement assign it the sum of 2 numbers. (You've learned only two rules for naming variables so far, so they're the only ones I'll hold you to.)

#### Answer:
{% highlight javascript %}
	var exercise;
	exercise = 2 + 2;
{% endhighlight %}

#### Question:
Live coding exercise: 
1) Declare a variable and assign it a number. 
2) Then code an alert, specifying the variable, not the number, as the message.

#### Answer:
{% highlight javascript %}
	var Number = 5;
	alert(Number);
{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare a variable and assign it a number.
2) Double the variable's value by adding the variable to itself.
3) Display the variable's value in an alert, specifying the variable, not the number, as the message.

#### Answer:
{% highlight javascript %}
	var Number = 5;
	Number = Number + Number;
	alert(Number);
{% endhighlight %}