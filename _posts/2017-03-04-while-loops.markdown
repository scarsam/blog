---
layout: posts
title:  "while loops"
tags: Javascript
---

#### Question:
The first line of a while operation sets the counter. Type the keyword that begins the second line, plus the 2 characters that follow the keyword.

#### Answer:
`while (`

#### Question:
What is the last character of the first line of a while statement?

#### Answer:
{

#### Question:
Instead of a while loop, you can always use a ______ loop.

#### Answer:
for loop

#### Question:
Type the last line of a while statement.

#### Answer:
}

#### Question:
Code the statement that needs to run above this line of code.
while (i <= 144) {

#### Answer:
`var i = 0;`

#### Question:
Code a while loop that runs twice and does nothing. The counter i has already been declared and assigned 0.

#### Answer:
{% highlight javascript %}

while (i <= 1) {
  i++;
}
or
while (i < 2) {
  i++;
}

{% endhighlight %}

#### Question:
I've declared two variables and assigned values to them. Code a while loop that adds i to tot with each iteration. Use i > 0 as the loop limiter.

{% highlight javascript %}

var tot = 0;
var i = 10;

{% endhighlight %}

#### Answer:
{% highlight javascript %}

while (i > 0) {
  tot = tot + i;
  i--;
}

{% endhighlight %}

#### Question:
Code the line of a while loop that begins with while. The loop runs as long as i is greater than 10.

#### Answer:
`while (i > 10) {`

#### Question:
I've coded an array, shown below. Code a while loop that looks for "pig" in the array. When it finds it, an alert displays saying, "Found it!" Use the length of the array as the loop limiter. Break out of the loop when it's found.

`var animals=["horse", "ox", "cow", "pig", "duck"];`

#### Answer:
{% highlight javascript %}

var i = 0;
while (i < animals.length) {
  if (animals[i] === "pig") {
    alert("Found it!");
    break;
  }
  i++;
}​

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code an alert that loops 3 times, alerting the value of the counter each time.

#### Answer:
{% highlight javascript %}

var i = 0;
while (i < 3) {
  alert(i);
  i++;
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) I've coded an array. Code a while loop that looks for "Tigers" in the array. When "Tigers" is found, an alert displays saying, "Tigers is at index [whatever its array index is] in the array." Use the length of the array as the loop limiter. Break out of the loop when "Tigers" is found. Don't change my code. Add your code below it.

{% highlight javascript %}

var teams = ["Chiefs", "Bees", "Tigers", "Bears"];

{% endhighlight %}

#### Answer:
{% highlight javascript %}

var teams = ["Chiefs", "Bees", "Tigers", "Bears"];
var i = 0;
while (i < teams.length) {
  if(teams[i] === "Tigers") {
    alert("Tigers is at index " + i + " in the array");
    break;
  }
  i++;
}

{% endhighlight %}
