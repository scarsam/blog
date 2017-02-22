---
layout: posts
title:  "Rounding numbers"
tags: Javascript
---

#### Question:
Fill in the blank to round to the nearest integer.
`var roundedNum = ___________(fractionalNum);`

#### Answer:
`var roundedNum = Math.round(fractionalNum);`

#### Question:
Fill in the blank to round up.
`var roundedNum = ___________(fractionalNum);`

#### Answer:
`var roundedNum = Math.ceil(fractionalNum);`

#### Question:
Fill in the blank to round down.
`var roundedNum = ___________(fractionalNum);`

#### Answer:
`var roundedNum = Math.floor(fractionalNum);`

#### Question:
What is the value of roundedNum?
`var roundedNum = Math.floor(1.9);`

#### Answer:
`roundedNum = 1;`

#### Question:
Round a number represented by a variable and assign the result to a second variable that hasn't been declared beforehand.

#### Answer:
`var roundNum = Math.round(origNum);`

#### Question:
Round down a number represented by a variable and assign the result to a second variable that hasn't been declared beforehand.

#### Answer:
`var roundDown = Math.floor(origNum);`

#### Question:
Round up a number represented by a variable and assign the result to a second variable that hasn't been declared beforehand.

#### Answer:
`var roundUpNum = Math.ceil(origNum);`

#### Question:
Round .5 to 0 and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var num = Math.floor(.5);`

#### Question:
Round .00001 to 1 and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var roundNum = Math.ceil(.00001);`

#### Question:
Live coding exercise:
1) In a single statement round a decimal number and display it in an alert.

#### Answer:
{% highlight javascript %}

alert(Math.round(0.5));

{% endhighlight %}

#### Question:
Live coding exercise:
1) In a single statement round down a negative decimal number and display it in an alert.

#### Answer:
{% highlight javascript %}

alert(Math.floor(-1.1));

{% endhighlight %}
