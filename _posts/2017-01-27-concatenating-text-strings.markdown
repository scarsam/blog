---
layout: posts
title:  "Concatenating text strings"
tags: Javascript
---

#### Question:
`var num = "2" + "2";`
What is the value of num? Include quotation marks.

#### Answer:
Strings cannot do math, so the value in `num` will be `"22"`.

#### Question:
What is it called when you combine two or more strings, using the plus sign?

#### Answer:
Concatenation.

#### Question:
`message = ("Hello," + "Dolly");`
What is the value of message? (Include the quotation marks.)

#### Answer:
`message = "Hello,Dolly";`

#### Question:
`alert("33" + 3);`
What message displays in the alert box?

#### Answer:
alert will display `333`.

#### Question:
Write a statement that assigns to a variable the concatenation of the two parts of "Oh yeah" (no period at the end). The second part is "yeah" The variable hasn't been declared beforehand.

#### Answer:
`var quote = "Oh " + "yeah";` See the space after "Oh " to create a space in the sentence.

#### Question:
Write a statement that concatenates two variables and assigns the result to a third variable. The third variable hasn't been declared beforehand.

#### Answer:
`var test = hello + hello2;`

#### Question:
Write a statement that displays an alert. The message is a string concatenated with a variable.

#### Answer:
`var num = "133" + 7;`

#### Question:
Assign strings to two variables. Then concatenate them and assign the result to a third variable. None of the variables have been declared beforehand.

#### Answer:
`var test = "hello";`
`var fest = "hello2";`
`var final = test + fest;`

#### Question:
Live coding exercise:
1) Assign a string to a variable. 
2) Display an alert, specifying the concatenation of the variable plus a string as the message.

#### Answer:
{% highlight javascript %}
	var test = "hello ";
	alert(test + "world");
{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign two strings to two variables.
2) Assign to a third variable the concatenation of the first two variables.
3) Display an alert, specifying the third variable as the message.

#### Answer:
{% highlight javascript %}
	var test = "hello ";
	var test2 = "world";
	var test3 = test + test2;
	alert(test3);
{% endhighlight %}