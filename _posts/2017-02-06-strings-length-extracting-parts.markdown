---
layout: posts
title:  "Strings: measuring length and extracting parts"
tags: Javascript
---

#### Question:
What is the method for extracting a segment from a string?

#### Answer:
slice

#### Question:
"captain" has been assigned to someWord. You want to slice "ap" out of it. Fill in the blank.
`var segment = someWord.slice(___);`

#### Answer:
`var segment = someWord.slice(1, 3);`

#### Question:
You want to take a slice out of the string that starts at the fifth character and goes to the end. Fill in the blank.
`var segment = someWord.slice(___);`

#### Answer:
`var segment = someWord.slice(4);`
The fifth character is index-4. When you provide no second index, JavaScript includes all character to the end. 

#### Question:
The number of characters in the string will be assigned to the variable. Fill in the blank.
`var numChars = someWord._______;`

#### Answer:
`var numChars = someWord.length();`

#### Question:
The string "elephant" has been assigned to the variable animal. Slice the four middle characters out of the string and assign it to the variable seg, which hasn't been declared beforehand.

#### Answer:
`var seg = animal.slice(2, 6);`

#### Question:
Find the number of characters in the string represented by a variable and assign the number to a second variable.

#### Answer:
`var num = hello.length;`

#### Question:
Assign the second through last characters of a variable to a second variable that hasn't been declared beforehand.

#### Answer:
`var seg = hello.slice(1);`

#### Question:
Assign the first character of a string represented by a variable to a second variable that has been declared beforehand.

#### Answer:
`seg = hello.slice(0, 1);`

#### Question:
In a first statement measure how many characters there are in a string represented by a variable. In a second statement slice all but the first and last characters of the string and assign it to a second variable that hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}

var numChars = cityToCheck.length;
var seg = cityToCheck.slice(1, numChars - 1);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign "elephant" to a variable.
2) Code an alert that displays the first 3 characters.

#### Answer:
{% highlight javascript %}

var animal = "elephant";
alert(animal.slice(0, 3));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Prompt for a long word.
2) Code an alert that displays the second through next-to-last characters.

#### Answer:
{% highlight javascript %}

var word = prompt("Enter a long word");
var wordLength = word.length; 
alert(word.slice(1, wordLength - 1));

{% endhighlight %}