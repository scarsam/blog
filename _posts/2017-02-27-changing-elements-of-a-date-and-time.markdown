---
layout: posts
title:  "Changing elements of a date and time"
tags: Javascript
---

#### Question:
You want to change the year of a Date object. What is the keyword?

#### Answer:
`setFullYear`

#### Question:
What is the keyword for adjusting the smallest unit of time in a Date object?

#### Answer:
`setMilliseconds`

#### Question:
If the original Date object is "January 1, 2001" what month is it after this statement executes? Spell out the month.
d.setMonth(7);

#### Answer:
August

#### Question:
To specify half a second, what number do you enclose in the parentheses?
d.setMilliseconds(_____);

#### Answer:
500

#### Question:
The Date object represented by d is the first month. Change it to the second month.

#### Answer:
`d.setMonth(1);`

#### Question:
Set a Date object represented by a variable of your choice to the year of the Millenium Bug.

#### Answer:
`bugHysteriaTime.setFullYear(2000);`

#### Question:
Set a Date object represented by a variable of your choice to the last second.

#### Answer:
`d.setSeconds(59);`

#### Question:
Set a Date object represented by a variable of your choice to the last hour.

#### Answer:
`d.setHours(23);`

#### Question:
Set a Date object represented by a variable of your choice that was originally "January 1, 2000 09:33:00" so it's "January 1, 2000 09:00:00".

#### Answer:
`dDay.setMinutes(0);`

#### Question:
Live coding exercise:
1) Create a Date object for the current date and time.
2) Extract the hours.
3) Reset the Date object an hour ahead.
4) Display the date Object in an alert.

#### Answer:
{% highlight javascript %}

var now = new Date();
var nowHours = now.getHours();
now.setHours(nowHours + 1);
alert(now);

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create a Date object for the current date and time.
2) Extract the year.
3) Reset the Date object a century back.
4) Display the date Object in an alert.

#### Answer:
{% highlight javascript %}

var d = new Date();
var year = d.getFullYear();
d.setFullYear(year - 100);
alert(d);

{% endhighlight %}
