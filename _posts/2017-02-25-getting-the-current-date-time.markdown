---
layout: posts
title:  "Getting the current date and time"
tags: Javascript
---

#### Question:
The statement below creates a Date _____.
var now = new Date();

#### Answer:
object

#### Question:
A date object looks like a _______ but isn't one.

#### Answer:
string

#### Question:
Two of the characters in this statement are incorrect. Type the correct characters in order, without a space separating them.
var currentDateAndTime = New date();

#### Answer:
var currentDateAndTime = new Date();

#### Question:
If it's Saturday, what is the value of thisDay?
var thisDay = now.getDay();

#### Answer:
`6` Days of the week range from 0 for Sunday to 6 for Saturday.

#### Question:
Code a statement that creates a new Date object and assigns it to d, which hasn't been declared beforehand.

#### Answer:
`var d = new Date();`

#### Question:
Code a statement that extracts the day of the week from a Date object represented by d and assigns it to day, which hasn't been declared beforehand.

#### Answer:
`var day = d.getDay();`

#### Question:
Code a statement that creates a new Date object and assigns it to a variable that hasn't been declared beforehand.

#### Answer:
`var a = new Date();`

#### Question:
Code a statement that extracts the day of the week from a Date object represented by a variable and assigns it to a variable that hasn't been declared beforehand.

#### Answer:
`var day = d.getDay();`

#### Question:
The day has been extracted from the Date object and assigned to d. The names of the days of the week have been assigned to the array dayNames. Fill in the blank.
`alert("Today is " + ___________);`

#### Answer:
`alert("Today is " + dayNames[d]);`

#### Question:
Live coding exercise:
1) Create a new Date object.
2) Code an alert that displays the number representing the current day.

#### Answer:
{% highlight javascript %}

var d = new Date();
alert(d.getDay());

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create a new Date object.
2) Extract the day.
3) Convert the day to a day name.
4) Code an alert that displays the day name.

#### Answer:
{% highlight javascript %}

var day = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
var dObj = new Date();
var today = dObj.getDay();
alert(day[today]);

{% endhighlight %}
