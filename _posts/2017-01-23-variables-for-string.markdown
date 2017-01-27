---
layout: posts
title:  "Variables for Strings"
tags: Javascript
---

#### Question:
What is a thing you create that refers to a value?

#### Answer:
Variable

#### Question:
In one word, if it is enclosed in quotation marks, what is it?

#### Answer:
String

#### Question:
What is the keyword that declares a variable?

#### Answer:
The keyword is `var`

#### Question:
This statement...`userName = "buddy5000";`
...is correct only if the variable has already been _______.

#### Answer:
Declared

#### Question:
This statement has already been coded.
{% highlight javascript %}
	var bestMan = "Charlie";
{% endhighlight %}
Assign the variable a new string value.

#### Answer:
Note that you don't need to declare the variable, because it was declared earlier.
{% highlight javascript %}
	bestMan = "Hello";
{% endhighlight %}

#### Question:
Live coding exercise: 
1) Declare a variable and assign it a string. 
2) Then code an alert, specifying the variable, not the string, as the message. 

#### Answer:
{% highlight javascript %}
	var testAlert = "exercise 2";
	alert(testAlert);
{% endhighlight %}

#### Question:
Live coding exercise: 
1) Declare a variable and assign it a string that's nothing but the name of the variable. 
2) Then code an alert, specifying the variable, not the string, as the message.

#### Answer:
{% highlight javascript %}
	var testAlert = "testAlert";
	alert(testAlert);
{% endhighlight %}