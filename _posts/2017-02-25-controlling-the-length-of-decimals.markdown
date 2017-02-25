---
layout: posts
title:  "Controlling the length of decimals"
tags: Javascript
---

#### Question:
The keyword that rounds a number to a specified number of decimal places and converts it to a string is _____.

#### Answer:
`toFixed`

#### Question:
A number modified by toFixed winds up as a ______. Answer with 1 word.

#### Answer:
string

#### Question:
To force toFixed to round up in the case of an ambiguity, change the last decimal value to a ____. Answer with a number.

#### Answer:
6

#### Question:
The statement will round the number to an integer. Fill in the blank.
var newNum = oldNum.toFixed___;

#### Answer:
var newNum = oldNum.toFixed();

#### Question:
Code a statement that rounds a number represented by n to 3 places, converts it to a string, and assigns it to dec3, which hasn't been declared beforehand.

#### Answer:
`var dec3 = n.toFixed(3);`

#### Question:
Code a statement that rounds a number represented by n to no places, converts it to a string, and assigns it to intgr, which hasn't been declared beforehand.

#### Answer:
`var intgr = n.toFixed();`

#### Question:
Code a statement that rounds a number represented by a variable to your choice of places, converts it to a string, and assigns it to another variable, which hasn't been declared beforehand.

#### Answer:
`var a = b.toFixed(2);`

#### Question:
Code a statement that rounds a number represented by a variable to no places, converts it to a string, and assigns it to the same variable.

#### Answer:
`var a = a.toFixed();`

#### Question:
In a single statement round a number represented by a variable to 2 places, convert it to a string, convert it back to a number, and assign it to the same variable.

#### Answer:
`n = Number(n.toFixed(2));`

#### Question:
Live coding exercise:
1) Assign a number with many decimal places to a variable.
2) Code an alert that displays the number rounded to 2 decimal places and converted to a string.

#### Answer:
{% highlight javascript %}

var num = 1337.123456
alert(num.toFixed(2));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a number with many decimal places to a variable.
2) Code an alert that displays the number rounded to no decimal places and converted to a string.

#### Answer:
{% highlight javascript %}

var num = 1337.223456
alert(num.toFixed());

{% endhighlight %}
