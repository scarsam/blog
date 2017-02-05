---
layout: posts
title:  "for loops: flags, Booleans, array length, and loopus interruptus"
tags: Javascript
---

#### Question:
In one word, what is a flag?

#### Answer:
variable

#### Question:
What is the keyword that stops a loop from continuing to loop?

#### Answer:
`break;`

#### Question:
There are two Booleans. Name either one of them.

#### Answer:
`true` and `false`

#### Question:
The statement assigns the number of elements in the array to the variable. Fill in the blank.
`var num = generals.________;`

#### Answer:
`length`

#### Question:
Set a flag with an initial Boolean value of your choice.

#### Answer:
{% highlight javascript %}

var flag = false;

{% endhighlight %}

#### Question:
Find the number of elements in an array and assign the number to a variable, which hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}

var elements = songbirds.length;

{% endhighlight %}

#### Question:
Code the first line of a for loop with the usual counter, the usual starting value, and the usual incrementing. Limit the number of loops by the number of elements in the array pets.

#### Answer:
{% highlight javascript %}

for (var i = 0; i < pets.length; i++) {

{% endhighlight %}

#### Question:
In 3 statements, assign a number to a variable that's already been declared, assign a Boolean (either one) to a flag that's already been declared, and interrupt a loop. Don't indent any of the lines.

#### Answer:
{% highlight javascript %}

num = 5;
flag = false;
break;

{% endhighlight %}

#### Question:
Complete this code to display an alert if a match isn't found.
var matchFound = false;
for (var i = 0; i < list.length; i++) {
  if (userInput === list[i]) {
    alert("Match found");
    matchFound = true;
    break;
  } 
}

#### Answer:
{% highlight javascript %}

if (matchFound === false) {
  alert("Match not found");
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Set a for loop to run 10 iterations.
2) On the second iteration, display the counter in an alert. (It should be 1.)
3) Break out of the loop

#### Answer:
{% highlight javascript %}

for (var i = 0; i < 10; i++) {
  if (i === 1) {
    alert(i);
    break;
  }
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create an array with 2 number elements.
2) Set a for loop, limiting the number of iterations using the length keyword.
3) Loop through the array to test whether each of the elements matches itself. (It will. )
4) When a match is found, display an alert with the number (it should be your first number) and stop the loop.

#### Answer:
{% highlight javascript %}

var nums = [10, 20];
for (var i = 0; i < nums.length; i++) { 
  if (nums[i] === nums[i]) {
    alert(nums[i]);
    break;
  }
}

{% endhighlight %}