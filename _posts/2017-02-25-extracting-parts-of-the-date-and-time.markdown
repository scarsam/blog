---
layout: posts
title:  "Extracting parts of the date and time"
tags: Javascript
---

#### Question:
What is the keyword for extracting the day of the month?

#### Answer:
getDate

#### Question:
What is the keyword for extracting the year?

#### Answer:
getFullYear

#### Question:
What is the keyword for extracting the milliseconds since midnight, Jan. 1, 1970?

#### Answer:
getTime

#### Question:
What is the keyword for extracting the smallest unit of time that JavaScript recognizes?

#### Answer:
getMilliseconds

#### Question:
The Date object is represented by d. Code a statement that displays the year in an alert.

#### Answer:
`alert(d.getFullYear());`

#### Question:
The Date object is represented by now. Code the first line of an if statement that tests whether it's the last quarter of the year.

#### Answer:
`if (now.getMonth() > 8) {`

#### Question:
Code a statement that determines the seconds since midnight, Jan. 1, 1970 and assigns it to a variable that hasn't been declared beforehand. Use any variable you like to represent the Date object. Note that I'm asking for seconds. Don't round it.

#### Answer:
`var secsSince = d.getTime() / 1000;`

#### Question:
Code the first line of an if statement that tests whether it's before noon. Use any variable you like to represent the Date object.

#### Answer:
`if (now.getHours() < 12) {`

#### Question:
Code the first line of an if statement that tests whether the clock is at an hour on the dot. Check minutes and then seconds. Ignore milliseconds. Use any variable you like to represent the Date object.

#### Answer:
`if (d.getMinutes() === 0 && d.getSeconds() === 0) {`

#### Question:
Live coding exercise:
1) Create a new Date object and assign it to a variable.
2) Code an alert that displays the current year.

#### Answer:
{% highlight javascript %}

var d = new Date();
alert(d.getFullYear());

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create a new Date object.
2) Extract the day.
3) Convert the day to a day name.
4) Code an alert that displays the day name.

#### Answer:
{% highlight javascript %}

var moNames = ["Jan", "Feb", "Mar", "Apr","May",
    "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];
var d = new Date();
var theMo = d.getMonth();
alert(moNames[theMo]);

{% endhighlight %}
