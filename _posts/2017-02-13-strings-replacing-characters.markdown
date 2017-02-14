---
layout: posts
title:  "Strings: replacing characters"
tags: Javascript
---

#### Question:
What is the keyword for removing one set of characters and inserting another set in its place?

#### Answer:
`replace`

#### Question:
After these two statements execute, what is the value of x? Include quotation marks.
`var x = "abc";`
`var y = x.replace("a", "z");`

#### Answer:
"abc" When the revised string is assigned to a new variable, the original string is preserved in the original variable. 

#### Question:
If you want all instances replaced, enter 3 characters that need to appear in this statement.
`var y = x.replace("a", "z");`

#### Answer:
`//g` The code for a global replace is:
`var y = x.replace(/a/g, "z");`

#### Question:
After these two statements execute, what is the value of x? Include quotation marks.
`var x = "abc abc";`
`x = x.replace("a", "z");`

#### Answer:
"zbc abc"
The statement replaces only the first instance.

#### Question:
In a string represented by str replace the first instance of "1" with "one" and assign the revised string to newStr, which hasn't been declared beforehand.

#### Answer:
`var newStr = str.replace("1", "one");`

#### Question:
In a string represented by str replace all instances of "1" with "one" and assign the revised string to newStr, which hasn't been declared beforehand.

#### Answer:
`var newStr = str.replace(/1/g, "one");`

#### Question:
In a string represented by a variable replace the first instance of one string with another and assign the revised string to the original variable.

#### Answer:
`var hello = hello.replace("walk", "dance");`

#### Question:
In a string represented by a variable replace all instances of one string with another and assign the revised string to the original variable.

#### Answer:
`var hello = hello.replace(/dance/g, "walk");`

#### Question:
The string "Move up" has been assigned to the variable direction. In a single statement and with the minimum amount of code, code an alert that specifies as the message the variable direction, but revised so it says "Move down"

#### Answer:
{% highlight javascript %}

alert(direction.replace("up", "down"));

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a string to a variable.
2) Replace a set of characters in it.
3) Display an alert, specifying the variable as the message.

#### Answer:
{% highlight javascript %}

var hello = "Hello Sam";
hello = hello.replace("Sam", "Mas");
alert(hello);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign "To be or not to be" to a variable.
2) Replace all instances of "be" with "party".
3) Display an alert, specifying the variable as the message.

#### Answer:
{% highlight javascript %}

var poem = "To be or not to be";
poem = poem.replace(/be/g, "party");
alert(poem);

{% endhighlight %}