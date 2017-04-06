---
layout: posts
title:  "Lambda School Assignment 2"
tags: Javascript
---

### Homework URL:
`https://github.com/SunJieMing/js-minicamp-homework-2`

#### Question:
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
* for loop
* && || !
* Array
* git
* GitHub

#### Answer:
* for loop
  * for loop is usually used to go through arrays. It's an quick an efficient way to run through values.
* && || !
  * These are called logical operators. These are often use to check if the value is a Boolean (true or false).
* Array
  * Array is like a variable (a box) that could hold multiple values at the same time.
* git
  * git is a version control system that is tracking changes in your work. This is very useful if you're multiple people working on the same files
* GitHub
  * Github is a service that can handle the git files. They have a website that will help you visualize and use the git files in a more easy way.

#### Question:
x and y are integers.  Return the larger integer. If they are the same return either one

#### Answer:
{% highlight javascript %}
function getBiggest(x, y) {
  if (x > y) {
    return x;
  }
  else if (y > x) {
    return y;
  }
  else {
    return x;
  }
}
{% endhighlight %}

#### Question:
Return a greeting for three different languages:
* language: 'German' -> 'Guten Tag!'
* language: 'English' -> 'Hello!'
* language: 'Spanish' -> 'Hola!'
* if language is undefined return 'Hello!'

#### Answer:
{% highlight javascript %}
function greeting(language) {
  if (language === 'German') {
    return 'Guten Tag!';
  }
  else if (language === 'English') {
    return 'Hello!';
  }
  else if (language === 'Spanish') {
    return 'Hola!';
  }
  else {
    return 'Hello!';
  }
}
{% endhighlight %}

#### Question:
Return true if num is 10 or 5. Otherwise return false

#### Answer:
{% highlight javascript %}
function isTenOrFive(num) {
  if (num === 10 || num === 5) {
    return true;
  }
  else {
    return false;
  }
}
{% endhighlight %}

#### Question:
Return true if num is less than 50 and greater than 20

#### Answer:
{% highlight javascript %}
function isInRange(num) {
  if (num < 50 && num > 20) {
    return true;
  }
  else {
    return false;
  }
}
{% endhighlight %}

#### Question:
Return true if num is an integer
* 0.8 -> false
* 1 -> true
* -10 -> true
Otherwise return false. Hint: you can solve this using Math.floor

#### Answer:
{% highlight javascript %}
function isInteger(num) {
  if (num === Math.floor(num)) {
    return true;
  }
  else {
    return false;
  }
}
{% endhighlight %}

#### Question:
* if num is divisible by 3 return 'fizz'
* if num is divisible by 5 return 'buzz'
* if num is divisible by 3 & 5 return 'fizzbuzz'
Otherwise return num

#### Answer:
{% highlight javascript %}
function fizzBuzz(num) {
  if (num % 3 === 0 && num % 5 === 0) {
    return 'fizzbuzz';
  }
  else if (num % 3 === 0) {
    return 'fizz';
  }
  else if (num % 5 === 0) {
    return 'buzz';
  }
  else {
    return num;
  }
}
{% endhighlight %}

#### Question:
Return true if num is prime. Otherwise return false
* hint: a prime number is only evenly divisible by itself and 1
* hint2: you can solve this using a for loop
Note: 0 and 1 are NOT considered prime numbers

#### Answer:
{% highlight javascript %}
function isPrime(num) {
  if (num === 0 || num === 1) {
    return false;
  }
  for (var i = 2; i < num; i++) {
    if (num % i === 0) {
      return false;
    }
  }
  return true;
}
{% endhighlight %}

#### Question:
Return the first item from the array

#### Answer:
{% highlight javascript %}
function returnFirst(arr) {
  return arr[0];
}
{% endhighlight %}

#### Question:
Return the last item of the array

#### Answer:
{% highlight javascript %}
function returnLast(arr) {
  return arr[arr.length - 1];
}
{% endhighlight %}

#### Question:
Return the length of the array

#### Answer:
{% highlight javascript %}
function getArrayLength(arr) {
  return arr.length;
}
{% endhighlight %}

#### Question:
arr is an array of integers. Increase each integer by one, return the array

#### Answer:
{% highlight javascript %}
function incrementByOne(arr) {
  for (var i = 0; i < arr.length; i++) {
    arr[i] = arr[i] + 1;
  }
  return arr;
}
{% endhighlight %}

#### Question:
Add the item to the end of the array. Return the array

#### Answer:
{% highlight javascript %}
function addItemToArray(arr, item) {
  arr.push(item);
  return arr;
}
{% endhighlight %}

#### Question:
Add the item to the front of the array. Return the array
* hint: use the array method .unshift

#### Answer:
{% highlight javascript %}
function addItemToFront(arr, item) {
  arr.unshift(item);
  return arr;
}
{% endhighlight %}

#### Question:
Words is an array of strings. Rreturn a string that is all of the words concatenated together. Spaces need to be between each word
* example: ['Hello', 'world!'] -> 'Hello world!'

#### Answer:
{% highlight javascript %}
function wordsToSentence(words) {
  var s = words.join(' ');
  return s;
}
{% endhighlight %}

#### Question:
Check to see if item is inside of arr. Return true if it is, otherwise return false

#### Answer:
{% highlight javascript %}
function contains(arr, item) {
  if (arr.indexOf(item) > -1) {
    return true;
  }
  else {
    return false;
  }
}
{% endhighlight %}

#### Question:
Numbers is an array of integers. Add all of the integers and return the value

#### Answer:
{% highlight javascript %}
function addNumbers(numbers) {
  var total = 0;
  for (var i = 0; i < numbers.length; i++) {
    total += numbers[i];
  }
  return total;
}
{% endhighlight %}

#### Question:
testScores is an array.  Iterate over testScores and compute the average. Return the average

#### Answer:
{% highlight javascript %}
function averageTestScore(testScores) {
  var total = 0;
  for (var i = 0; i < testScores.length; i++) {
    total += testScores[i];
  }
  var average = total / testScores.length;
  return average;
}
{% endhighlight %}

#### Question:
Numbers is an array of integers. Return the largest integer

#### Answer:
{% highlight javascript %}
function largestNumber(numbers) {
  var biggestNum = 0;
  for (var i = 0; i < numbers.length; i++) {
    if (numbers[i] > biggestNum) {
      biggestNum = numbers[i];
    }
  }
  return biggestNum;
}
{% endhighlight %}
