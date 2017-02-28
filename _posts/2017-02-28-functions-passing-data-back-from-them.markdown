---
layout: posts
title:  "Functions: passing data back from them"
tags: Javascript
---

#### Question:
The keyword that sends data back to the calling code is ______.

#### Answer:
return

#### Question:
You can use a function in any place where you would use a ________.

#### Answer:
variable

#### Question:
When a function sends data back to the calling code, the calling code needs something to catch it. That something is usually a ________.

#### Answer:
variable

#### Question:
If a function has 3 parameters, how many values can be returned to the calling code? Answer with a numeral.

#### Answer:
`1` The number of parameters is irrelevant, since only 1 value can be returned.

#### Question:
Code a function call that has two arguments. The first argument is a variable. The second argument is another function call. The second function call takes the argument 10. The value returned by the first function is assigned to est, which hasn't been declared beforehand.

#### Answer:
`var est = makeEst(empNum, calcBonus(10));`

#### Question:
Code a function with two parameters that passes back the values of the parameters multiplied by each other. Use minimal code. That is, don't assign the product of the multiplication to a variable.

#### Answer:
{% highlight javascript %}

function mult(param1, param2) {
  return param1 * param2;
}

{% endhighlight %}

#### Question:
Code a statement that assigns to a variable (that hasn't been declared beforehand) the arithmetic sum of two function calls. The function calls take no arguments.

#### Answer:
`var total = dance() + dance2();`

#### Question:
Code an alert. Specify as the message a function call that takes two literal strings as arguments.

#### Answer:
`alert(msg("hello ", "dance"));`

#### Question:
Code a function that has three parameters to which numbers are passed. Add them and assign the total to a variable that hasn't been declared beforehand. If the number is greater than 0, return it to the calling code.

#### Answer:
{% highlight javascript %}

function hello(param1, param2, param3) {
  var total = param1 + param2 + param3;
  if (total > 0) {
    return total;
  }
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) I've coded a function. Code an alert, calling the function to create the message for the alert. Leave my code as-is. Add your code below it.

{% highlight javascript %}

function computeInterest(principal, percentage) {
  return principal * percentage;
}

{% endhighlight %}


#### Answer:
{% highlight javascript %}

function computeInterest(principal, percentage) {
  return principal * percentage;
}
alert(computeInterest(100, 200));

{% endhighlight %}

#### Question:
Live coding exercise:
1) I've coded a function call that concatenates two text fragments to create a message for the alert. Code the function. Leave my code as-is. Add your code below it.

{% highlight javascript %}

alert(concatFrags("It is ", "what it is."));

{% endhighlight %}

#### Answer:
{% highlight javascript %}

alert(concatFrags("It is ", "what it is."));
function concatFrags(param1, param2) {
  return param1 + param2;
}

{% endhighlight %}
