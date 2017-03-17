---
layout: posts
title:  "Lambda School Assignment 1"
tags: Javascript
---

### Homework URL:
`https://github.com/SunJieMing/js-minicamp-homework-1`

#### Question:
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
* Variables
* Strings
* Functions (arguments, return)
* if statements
* Boolean values (true, false)

#### Answer:
* Variables
  * Variable is like a box that can store things in. You can name your box whatever you want and at a later stage refer to the name of the box to see what's in it.
* Strings
* Functions (arguments, return)
* if statements
* Boolean values (true, false)

#### Question:
Return num after multiplying it by ten.

#### Answer:
{% highlight javascript %}
function multiplyByTen(num) {
  var multi = num * 10;
  return multi;
}
{% endhighlight %}

#### Question:
Return num after subtracting five.

#### Answer:
{% highlight javascript %}
function subtractFive(num) {
  var subtr = num - 5;
  return subtr;
}
{% endhighlight %}

#### Question:
Return true if the two strings have the same length, otherwise return false.

#### Answer:
{% highlight javascript %}
function areSameLength(str1, str2) {
  if (str1.length === str2.length) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
Return true if x and y are the same, otherwise return false.

#### Answer:
{% highlight javascript %}
function areEqual(x, y) {
  if (x === y) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
Return true if num is less than ninety, otherwise return false.

#### Answer:
{% highlight javascript %}
function lessThanNinety(num) {
  if (num < 90) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
Return true if num is greater than fifty, otherwise return false.

#### Answer:
{% highlight javascript %}
function greaterThanFifty(num) {
  if (num > 50) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
Add x and y together and return the value.

#### Answer:
{% highlight javascript %}
function add(x, y) {
  var sum = x + y;
  return sum;
}
{% endhighlight %}

#### Question:
Subtract y from x and return the value.

#### Answer:
{% highlight javascript %}
function subtract(x, y) {
  var subtract = x - y;
  return subtract;
}
{% endhighlight %}

#### Question:
Divide x by y and return the value.

#### Answer:
{% highlight javascript %}
function divide(x, y) {
  var divide = x / y;
  return divide;
}
{% endhighlight %}

#### Question:
Multiply x by y and return the value.

#### Answer:
{% highlight javascript %}
function multiply(x, y) {
  var multiply = x * y;
  return multiply;
}
{% endhighlight %}

#### Question:
Return the remainder from dividing x by y.

#### Answer:
{% highlight javascript %}
function getRemainder(x, y) {
  var modulus = x % y;
  return modulus;
}
{% endhighlight %}

#### Question:
Return true if num is even, Otherwise return false.

#### Answer:
{% highlight javascript %}
function isEven(num) {
  if (num %2 === 0) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
Return true if num is false, otherwise return false.

#### Answer:
{% highlight javascript %}
function isOdd(num) {
  if (num %2 === 1) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
Square num and return the new value.

#### Answer:
{% highlight javascript %}
function square(num) {
  var square = Math.pow(num, 2);
  return square;
}
{% endhighlight %}

#### Question:
Cube num and return the new value.

#### Answer:
{% highlight javascript %}
function cube(num) {
  var cube = Math.pow(num, 3);
  return cube;
}
{% endhighlight %}

#### Question:
Raise num to whatever power is passed in as exponent.

#### Answer:
{% highlight javascript %}
function raiseToPower(num, exponent) {
  var raise = Math.pow(num, exponent);
  return raise;
}
{% endhighlight %}

#### Question:
Round num and return it.

#### Answer:
{% highlight javascript %}
function roundNumber(num) {
  var roundNum = Math.round(num);
  return roundNum;
}
{% endhighlight %}

#### Question:
Round num up and return it.

#### Answer:
{% highlight javascript %}
function roundUp(num) {
  var roundUpNum = Math.ceil(num);
  return roundUpNum;
}
{% endhighlight %}

#### Question:
Add an exclamation point to the end of str and return the new string
`'hello world' -> 'hello world!'`

#### Answer:
{% highlight javascript %}
function addExclamationPoint(str) {
  var newStr = str + '!';
  return newStr;
}
{% endhighlight %}

#### Question:
Return firstName and lastName combined as one string and separated by a space.
`'Lambda', 'School' -> 'Lambda School'`

#### Answer:
{% highlight javascript %}
function combineNames(firstName, lastName) {
  var lambdaSchool = firstName + ' ' + lastName;
  return lambdaSchool;
}
{% endhighlight %}

#### Question:
Take the name string and concatenate other strings onto it so it takes the following form: `'Sam' -> 'Hello Sam!'`

#### Answer:
{% highlight javascript %}
function getGreeting(name) {
  var greeting = 'Hello ' + name + '!';
  return greeting;
}
{% endhighlight %}

#### Question:
Return the area of the rectangle by using length and width.

#### Answer:
{% highlight javascript %}
function getRectangleArea(length, width) {
  var rectangleArea = length * width;
  return rectangleArea;
}
{% endhighlight %}

#### Question:
Return the area of the triangle by using base and height.

#### Answer:
{% highlight javascript %}
function getTriangleArea(base, height) {
  var triangleArea = (base * height) / 2;
  return triangleArea;
}
{% endhighlight %}

#### Question:
Return the rounded area of the circle given the radius.

#### Answer:
{% highlight javascript %}
function getCircleArea(radius) {
  var circleRadius = Math.PI * Math.pow(radius, 2);
  return Math.round(circleRadius);
}
{% endhighlight %}

#### Question:
Return the volume of the 3D rectangular prism given the length, width, and height.

#### Answer:
{% highlight javascript %}
function getRectangularPrismVolume(length, width, height) {
  var rectPrismVolume = length * width * height;
  return rectPrismVolume;
}
{% endhighlight %}
