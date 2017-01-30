---
layout: posts
title:  "Arrays: adding and removing elements"
tags: Javascript
---

#### Question:
This code declares an empty array. Complete it.
`var finalScores = ____`

#### Answer:
`var finalScores = [];`

#### Question:
counties is an empty array. What is the value of counties[0]?

#### Answer:
`undefined`

#### Question:
What keyword removes the last element from an array?

#### Answer:
`pop`

#### Question:
What keyword adds one or more elements to the end of an array?

#### Answer:
`push`

#### Question:
Create an empty array.

#### Answer:
{% highlight javascript %}

var a = [];

{% endhighlight %}

#### Question:
Change the value of the first element of an array to a new string.

#### Answer:
{% highlight javascript %}

var a[0] = "hello";

{% endhighlight %}

#### Question:
Add a new element, a number, to the end of an array.

#### Answer:
{% highlight javascript %}

prices.push(99);

{% endhighlight %}

#### Question:
Assign string values to the second and fourth elements of an array.

#### Answer:
{% highlight javascript %}

names[1] = "Sue";
names[3] = "Kate"; 

{% endhighlight %}

#### Question:
Add three number elements to end of an array.

#### Answer:
{% highlight javascript %}

prices.push(59, 79, 99);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Declare an empty array.
2) Assign a value to one of its elements.
3) Create an alert whose message is the element.

#### Answer:
{% highlight javascript %}

var a = [];
a[0] = 144;
alert(a);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code an array with 1 string element.
2) Add an additional element to the array using push.
3) Create an alert whose message is the last element.

#### Answer:
{% highlight javascript %}

var hello = ["hello"];
hello.push("dance");
alert(hello[1]);

{% endhighlight %}