---
layout: posts
title:  "Variable Names Legal and Illegal"
tags: Javascript
---

#### Question:
Type the illegal character in this statement.

#### Answer:
` ` space

#### Question:
Type the illegal character in this statement.
`var P2_a%88$;`

#### Answer:
`_%`

#### Question:
Rewrite this using camelCase.
`var Nameofband;`

#### Answer:
`var nameOfBand;` variable names should start with lowercase.

#### Question:
Declare a variable using nothing but all of the legal characters that aren't alphabet characters or numbers. Don't repeat any of them.

#### Answer:
`var _$;` or `var $_;`

#### Question:
In a single statement declare a legally-named variable and assign a number to it.

#### Answer:
{% highlight javascript %}
	var exercise = 10;
{% endhighlight %}

#### Question:
In a single statement declare a legally-named variable and assign to it the sum of 2 other legally-named variables.

#### Answer:
{% highlight javascript %}
	var exercise = test + test2;
{% endhighlight %}

#### Question:
Declare a variable whose name is the combination of 3 characters, in this order: a legal first character that is not a letter, a character that would be illegal as a first character, and a character that would be legal anywhere in the name.

#### Answer:
{% highlight javascript %}
	var _0l;
{% endhighlight %}

#### Question:
The variable `boogieWoogie` has already been declared. Assign to it the value of another variable, `woogieBoogie`.

#### Answer:
{% highlight javascript %}
	boogieWoogie = woogieBoogie;
{% endhighlight %}

#### Question:
Declare a variable that is a combination of your first and last names. Use camelCase.

#### Answer:
{% highlight javascript %}
	var samOjling;
{% endhighlight %}

#### Question:
Live coding exercise:
Declare a variable whose name is your first and last names combined, in camelCase.
Assign the variable your first and last names, as a string.
Code an alert, specifying the variable, not the string, as the message.
Click the Run It button to run your code live.

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
	var samOjling;
	samOjling = "Sam Ojling";
	alert(samOjling);
{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare a variable that combines a number, an alphabet letter, and one of the legal characters that are neither an alphabet letter nor a number.
2) Assign to the variable a string consisting of another legal character that is neither an alphabet letter nor a number.
3) Display the variable's value in an alert, specifying the variable, not the value, as the message.

#### Answer:
{% highlight javascript %}
	var b4$;
	b4$ = "_";
	alert(b4$);
{% endhighlight %}