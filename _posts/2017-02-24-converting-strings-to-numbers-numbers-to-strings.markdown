---
layout: posts
title:  "Converting strings to numbers, numbers to strings"
tags: Javascript
---

#### Question:
What is the keyword for converting an integer string or floating-point number string, to its equivalent number?

#### Answer:
`Number`

#### Question:
What is the keyword for converting a number to a string?

#### Answer:
`toString`

#### Question:
Type the characters that are missing from this statement.
`var myString = myNum.toString;`

#### Answer:
`()` the correct statement is var myString = myNum.toString();

#### Question:
num1 is "1", num2 is "3". Rewrite this statement so sum is assigned 4.
var sum = num1 + num2;

#### Answer:
var sum = Number(num1) + Number(num2);

#### Question:
Convert a string represented by myStr to a number and assign it to num, which hasn't been declared beforehand.

#### Answer:
`var num = Number(myStr);`

#### Question:
Convert a number represented by num to a string and assign it to myStr, which hasn't been declared beforehand.

#### Answer:
`var myStr = num.toString();`

#### Question:
Convert a string represented by a variable to a number and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var a = Number(b);`

#### Question:
Convert a number represented by a variable to a string and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var a = b.toString();`

#### Question:
Code the first line of an if statement that tests whether a string represented by a variable, converted to an integer, is greater than 1.

#### Answer:
`if (Number(myString) > 1) {`

#### Question:
Live coding exercise:
1) Assign a string, a number enclosed by quotation marks, to a variable.
2) Code an alert that displays the sum of the number, converted to a number, added to itself.

#### Answer:
{% highlight javascript %}

var a = "10";
alert(Number(a) + Number(a));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a number to a variable.
2) Code an alert that displays the number, converted to a string, concatenated to itself.
#### Answer:
{% highlight javascript %}

var a = 10;
alert(a.toString() + a.toString());

{% endhighlight %}
