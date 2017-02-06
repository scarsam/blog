---
layout: posts
title:  "Nested for loops"
tags: Javascript
---

#### Question:
If an outer loop runs 3 times and an inner loop runs 5 times, how many times will the inner loop iterate? Answer with a numeral.

#### Answer:
15

#### Question:
The outer loop and inner loop can't share the same ______. Answer with one word.

#### Answer:
counter

#### Question:
What's missing from this code? Answer with a 6-letter word that starts with "i".
{% highlight javascript %}

for (var i = 0; i <= array1Length; i++) {
for (var j = 0; j < array2Length; j++) {
sumOfCounters = i + j;
}
}

{% endhighlight %}

#### Answer:
indent

#### Question:
In the following nonsensical code, how many times will the outer loop execute? Answer with a numeral.
{% highlight javascript %}

for (var i = 0; i < 3; i++) {
  for (var j = 0; j < 10; j++) {
    if (j >= 1) {
      break;
    } 
  }
}

{% endhighlight %}

#### Answer:
`3` Even though the inner loop stops prematurely each time, there's nothing to stop the outer loop from iterating to its limit. 

#### Question:
Code an inner loop, including indentation, that doesn't do anything. Use any counter other than i. Use the usual starting value. Run it 10 times for each outer loop iteration. Increment by 1.

#### Answer:
{% highlight javascript %}

  for (j = 0; j < 10; j++) {
    alert("hello");
  }

{% endhighlight %}

#### Question:
Code an inner loop, including indentation, that assigns a number to a variable that has been declared beforehand. Use any counter other than i. Declare it with the usual starting value. Limit iterations by the number of elements in an array. Increment by 1.

#### Answer:
{% highlight javascript %}

  for (var j = 0; j < hello.length; j++) {
    dance = 5;
  }

{% endhighlight %}

#### Question:
Code nested loops that do nothing. Start counters at zero. The outer loop runs 5 times. The inner loop runs 5 times each time the outer loop iterates. Increment by 1.

#### Answer:
{% highlight javascript %}

for (var i = 0; i < 5; i++) {
  for (var j = 0; j < 5; j++) {
  }
}

{% endhighlight %}

#### Question:
Code nested loops. The inner loop adds the two counters and assigns the sum to a variable that has been declared beforehand. Start counters at zero. The outer loop runs 5 times. The inner loop runs 5 times each time the outer loop iterates. Increment by 1.

#### Answer:
{% highlight javascript %}

for (var i = 0; i < 5; i++) {
  for (var j = 0; j < 5; j++) {
    hello = i + j;
  }
}

{% endhighlight %}

#### Question:
Here are 4 lines of code.
{% highlight javascript %}

  var animals = ["goat", "cat", "crow"];
  var products = ["milk", "cheese", "burger"];
  var foodItems = [];
  var k = 0;

{% endhighlight %}

Continue the code to create nested loops. The inner loop concatenates each of the elements of animals with each of the elements of products, with no space separating them. Accumulate the combinations in foodItems. The counter for foodItems is k. Limit the number of loops by the length of each array.

#### Answer:
{% highlight javascript %}

for (var i = 0; i < animals.length; i++) {
  for (var j = 0; j < products.length; j++) {
    foodItems[k] = animals[i] + products[j];
    k++;
  }
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code nested loops. The outer loop runs twice. The inner loop runs twice for each outer loop iteration.
2) On each iteration of the inner loop, display the sum of the two counters in an alert.

#### Answer:
{% highlight javascript %}

for (var i = 0; i < 2; i++) {
  for (var j = 0; j < 2; j++) {
    alert(i + j);
  }
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create two 2-element arrays.
2) Create an empty array to accumulate concatenations. Create a counter for this array.
3) Code nested loops that concatenate all the combinations of the array elements.
4) After the loops have run, create an alert that displays the first combination.

#### Answer:
{% highlight javascript %}

var fruits = ["lemon ", "orange "];
var variations = ["juice", "curd"];
var products = [];
var h = 0; 
for (var i = 0; i < fruits.length; i++) { 
  for (var j = 0; j < variations.length; j++) { 
    products[h] = fruits[i] + variations[j];
    h++;
  }
}
alert(products[0]);

{% endhighlight %}