---
layout: posts
title:  "Strings: finding segments"
tags: Javascript
---

#### Question:
What is the keyword for finding the index of the first character of a segment?

#### Answer:
`indexOf()`

#### Question:
What is the keyword for finding the index of the first character of the last instance of a segment?

#### Answer:
`lastIndexOf()`

#### Question:
`var text = "To be or not to be.";`
`var indx = text.indexOf("be");`
What is the value of indx?

#### Answer:
3

#### Question:
`var text = "To be or not to be.";`
`var indx = text.lastIndexOf("be");` 
What is the value of indx?

#### Answer:
16

#### Question:
Find the index of the first character of the first instance of a literal string segment in a string represented by a variable, and assign it to another variable, which hasn't been declared beforehand.

#### Answer:
`var newVar = indexOf(literal);`

#### Question:
Find the index of the first character of the last instance of a literal string segment in a string represented by a variable, and assign it to another variable, which hasn't been declared beforehand.

#### Answer:
`var newVar = str.lastIndexOf("x");`

#### Question:
Code the first line of an if statement that tests whether a segment with an index represented by indexNum exists in a string.

#### Answer:
`if (indexNum !== -1) { ` This is because `indexOf()` and `lastIndexOf()` will return `-1` if it cannot find a match. Including `!==` in the if statment is like saying if it doesn't return `-1` it did find a match so please continue.

#### Question:
Code an alert that displays the index number of the first character of a segment represented by a variable that occurs within a string represented by a second variable.

#### Answer:
`alert(paragraph.indexOf(segment));

#### Question:
Code the first line of an if statement that tests whether a 3-character slice at the beginning of a string represented by one variable can be found somewhere within a string represented by a second variable.

#### Answer:
`if (var2.indexOf(var1.slice(0, 3)) !== -1) { `

#### Question:
Live coding exercise:
1) Assign a string to a variable.
2) Code an alert that displays the index of a segment that occurs in the string.

#### Answer:
{% highlight javascript %}

var str = "hello Sam";
alert(str.indexOf("Sam"));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a string to a variable.
2) Code an alert that displays the index of a segment that doesn't occur in the string.

#### Answer:
{% highlight javascript %}

var str = "Hello world";
alert(str.indexOf("code"));

{% endhighlight %}