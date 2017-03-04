---
layout: posts
title:  "do...while loops"
tags: Javascript
---

#### Question:
What is the nonspace character that always precedes the while clause in a do...while loop?

#### Answer:
}

#### Question:
What is the last character of a do...while loop?

#### Answer:
;

#### Question:
Type the two characters that follow the first keyword in a do...while loop.

#### Answer:
` {`

#### Question:
How many times will the alert be displayed? (Type a numeral.)

{% highlight javascript %}

var i = 0;
do {
  alert(i);
  i++;
} while (i < 0);

{% endhighlight %}

#### Answer:
1

#### Question:
Code the statement that needs to run above this line of code.

{% highlight javascript %}

do {
  alert(i);
  i++;

{% endhighlight %}

#### Answer:
`var i = 0;`

#### Question:
Code a do...while loop that runs 12 times and does nothing. The counter i has already been declared and assigned 0.

#### Answer:
{% highlight javascript %}

do {
  i++;
} while (i <= 11);
or
do {
  i++;
} while (i < 12);

{% endhighlight %}

#### Question:
I've declared two variables and assigned values to them. Code a do...while loop that adds i to tot with each iteration. Use i > 0 as the loop limiter.

{% highlight javascript %}

var tot = 0;
var i = 10;

{% endhighlight %}

#### Answer:
{% highlight javascript %}

do {
  tot = tot + i;
  i--;
} while (i > 0);

{% endhighlight %}

#### Question:
Code a do...while loop that alerts the counter with each iteration. Begin with the statement that initializes the counter. Run the loop as long as you like.

#### Answer:
{% highlight javascript %}

var i = 0;
do {
  alert(i);
  i++;
} while (i < 5);

{% endhighlight %}

#### Question:
I've coded an array. Code a do...while loop that looks for "pig" in the array. When it finds it, an alert displays saying, "Found it!" Use the length of the array as the loop limiter. Break out of the loop when "pig" is found.

`var animals=["horse", "ox", "cow", "pig", "duck"];`

#### Answer:
{% highlight javascript %}

var i = 0;
do {
  if (animals[i] === "pig") {
    alert("Found it!");
    break;
  }
  i++;
} while (i < animals.length);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Using a do...while loop, code an alert that loops 3 times, alerting the value of the counter each time.

#### Answer:
{% highlight javascript %}

var i = 0;
do {
  alert(i);
  i++;
} while (i < 3);


{% endhighlight %}

#### Question:
Live coding exercise:
1) I've coded an array. Code a do...while loop that looks for "Tigers" in the array. When "Tigers" is found, an alert displays saying, "Tigers is number [whatever its array number is] in the array." Use the length of the array as the loop limiter. Break out of the loop when "Tigers" is found. Don't change my code. Add your code below it.

{% highlight javascript %}

var teams = ["Chiefs", "Bees", "Tigers", "Bears"];

{% endhighlight %}

#### Answer:
{% highlight javascript %}

var teams = ["Chiefs", "Bees", "Tigers", "Bears"];
var i = 0;
do {
  for (teams[i] === "Tigers") {
    alert("Tigers is number " + i + " in the array.");
    break;
  }
  i++;
} while (i < teams.length);

{% endhighlight %}
