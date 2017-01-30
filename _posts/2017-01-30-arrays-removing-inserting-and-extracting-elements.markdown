---
layout: posts
title:  "Arrays: removing, inserting, and extracting elements"
tags: Javascript
---

#### Question:
What keyword removes the first element of an array?

#### Answer:
`shift`

#### Question:
What keyword adds one or more elements to the beginning of an array?

#### Answer:
`unshift`

#### Question:
What keyword inserts new elements anywhere in an array and/or removes elements from an array?

#### Answer:
`splice`

#### Question:
What keyword copies elements from an array to another array?

#### Answer:
`slice`

#### Question:
This statement created the array:
`var sizes = ["S", "M", "XL", "XXL", "XXXL"];`
Insert "L" into the array between "M" and "XL".

#### Answer:
{% highlight javascript %}

sizes.splice(2, 0, "L");

{% endhighlight %}

#### Question:
This statement created the array:
`var sizes = ["S", "M", "XL", "XXL", "XXXL"];`
Copy the first 3 sizes of the array and put them into a new array, regSizes.

#### Answer:
{% highlight javascript %}

var regSizes = size.slice(0, 3);

{% endhighlight %}

#### Question:
Remove the first element of an array.

#### Answer:
{% highlight javascript %}

airlines.shift();

{% endhighlight %}

#### Question:
Add three number elements to the beginning of an array.

#### Answer:
{% highlight javascript %}

scores.unshift(0, 13, 5);

{% endhighlight %}

#### Question:
This statement created the array:
`var pets = ["dog", "cat", "ox", "duck", "frog"];
Add 2 elements after "dog" and remove "cat", "ox", and "duck".

#### Answer:
{% highlight javascript %}

pets.splice(1, 3, "bear", "snake");

{% endhighlight %}

#### Question:
This statement created the array:
var pets = ["dog", "cat", "ox", "duck", "frog"];
Remove "cat" and "ox".

#### Answer:
{% highlight javascript %}

pets.splice(1, 2); 

{% endhighlight %}

#### Question:
This statement created the array:
var pets = ["dog", "cat", "ox", "duck", "frog", "flea"];
Reduce it to "duck" and "frog" using slice.

#### Answer:
{% highlight javascript %}

pets = pets.slice(3, 5);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare an array with one element.
2) Add a second element to the beginning of the array.
3) Create an alert whose message is the new first element.

#### Answer:
{% highlight javascript %}

var hello = ["car"];
hello.unshift("volvo");
alert(hello);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare an array with two elements.
2) Remove the first element.
3) Create an alert whose message is the new first element.

#### Answer:
{% highlight javascript %}

var hello = [1, 2];
hello.shift();
alert(hello);

{% endhighlight %}