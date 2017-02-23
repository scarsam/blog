---
layout: posts
title:  "Converting strings to integers and decimals"
tags: Javascript
---

#### Question:
What is the keyword for converting "1.5" to 1?

#### Answer:
`parseInt`

#### Question:
What is the keyword for converting "1.5" to 1.5?

#### Answer:
`parseFloat`

#### Question:
If JavaScript encounters a number inside quotation marks in an arithmetic expression, it temporarily converts it to a number and does the math, unless the expression includes.... Type the character.

#### Answer:
`+`

#### Question:
What is the value of num?
`var num = parseInt("5.6");``

#### Answer:
5 `parseInt` doesn't round. It just lops off the decimal value.

#### Question:
Convert a string represented by a variable to an integer and assign it to a second variable that hasn't been declared beforehand.

#### Answer:
`var a = parseInt(b);`

#### Question:
Convert a string represented by a variable to a number with a decimal value and assign it to a second variable that hasn't been declared beforehand.

#### Answer:
`var a = parseFloat(b);`

#### Question:
The string "1.99" has been assigned to price. In a single statement convert it to 1 and assign the result to the same variable.

#### Answer:
`var price = parseInt(price);`

#### Question:
In a single statement code an alert that displays the sum, including decimals, of 2 different strings represented by variables, converted to numbers.

#### Answer:
`alert(parseFloat(a) + parseFloat(b));`

#### Question:
Code the first line of an if statement that tests whether a string represented by a variable, converted to an integer, is greater than 1.

#### Answer:
`if (parseInt(a) > 1) {`

#### Question:
Live coding exercise:
1) Assign a string, a number enclosed by quotation marks, to a variable.
2) Code an alert that displays the sum of the number, converted to an integer, added to itself.

#### Answer:
{% highlight javascript %}

var num = "10";
alert(parseInt(num) + parseInt(num));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a string, a floating-point number enclosed by quotation marks, to a variable.
2) Code an alert that displays the sum of the number, converted to a floating-point number, added to itself.
#### Answer:
{% highlight javascript %}

var num = "1.5";
alert(parseFloat(num) + parseFloat(num));

{% endhighlight %}
