---
layout: posts
title:  "Strings: finding a character at a location"
tags: Javascript
---

#### Question:
What is the keyword for finding a character at a particular location in a string?

#### Answer:
`charAt`

#### Question:
In this string, what character is at index 2?—
"abcde"
Don't include quotation marks in your answer.

#### Answer:
c

#### Question:
Type the characters that are incorrect.
`var cha = sentence.charAt[10];`

#### Answer:
`[]` it should be `()`

#### Question:
The last character of the string is assigned to the variable. Fill in the blank, using the string length to specify the index.
var lastChar = str.charAt(________);

#### Answer:
`var lastChar = str.charAt(str.length - 1);`

#### Question:
Find the the first character in a string represented by str and assign it to x, which hasn't been declared beforehand.

#### Answer:
`var x = str.charAt(0);`

#### Question:
Find the the 5th character in a string represented by input and assign it to cha, which hasn't been declared beforehand.

#### Answer:
`var cha = input.charAt(4);`

#### Question:
Assign the second through last characters of a variable to a second variable that hasn't been declared beforehand.

#### Answer:
`var x = hello.charAt(hello.length - 1);`

#### Question:
Code the first line of an if statement that tests whether the 3rd character of a string represented by a variable is a particular character.

#### Answer:
`if (hello.charAt(2) === "h") {`

#### Question:
Code a for loop that cycles through all the characters of a string represented by a variable and assigns each character to an element of an array that has been declared beforehand.

#### Answer:
{% highlight javascript %}

for (var i = 0; i < text.length; i++) {
  textArray[i] = text.charAt(i);
} 

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a string to a variable.
2) Specifying the variable in the message, code an alert that displays the first character of the string.

#### Answer:
{% highlight javascript %}

var hello = "hello";
alert(hello.charAt(0));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a string to a variable.
2) Specifying the variable in the message, code an alert that displays the last character of the string.

#### Answer:
{% highlight javascript %}

var hello = "hello";
alert(hello.charAt(hello.length - 1));

{% endhighlight %}