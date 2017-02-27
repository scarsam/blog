---
layout: posts
title:  "Specifying a date and time"
tags: Javascript
---

#### Question:
You're creating a Date object for the first day of the first month of the year 2000. Fill in the blank. Use the date style taught in the book.
var prevDate = new Date(______________);

#### Answer:
`var prevDate = new Date("January 1, 2000")`

#### Question:
You're creating a Date object for noon on the dot. Fill in the blank.
var prev = new Date("January 1, 2000 _______");

#### Answer:
var prev = new Date("January 1, 2000, 12:00:00")

#### Question:
What is the keyword for extracting the basic time unit you need for figuring intervals?

#### Answer:
`getTime` You start with milliseconds, then convert it to days, hours, or whatever you need.

#### Question:
The statement converts milliseconds to hours. Fill in the blank. Use the multiplication formula taught in the book.
var hrs = ms / (__________);

#### Answer:
var hrs = ms / 1000 * 60 * 60

#### Question:
Create a Date object for the second day of the second month of 1992 and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var dOjb = new Date("February 2, 1992");`

#### Question:
Create a Date object for the first second of the first day of the first month of 1901 and assign it to a variable that hasn't been declared beforehand.

#### Answer:
`var earlyTime = new Date("January 1, 1901 00:00:01");`

#### Question:
Code a single statement that displays in an alert the milliseconds that elapsed between the reference date and the beginning of 1980.

#### Answer:
`alert(new Date("January 1, 1980").getTime());`

#### Question:
Code a statement that converts the milliseconds represented by ticks to hours and assigns the result to a variable that hasn't been declared beforehand.

#### Answer:
`var hrs = ticks / (1000 * 60 * 60);`

#### Question:
Code the first line of an if statement that tests whether the milliseconds represented by ms convert to more than 30 days.

#### Answer:
`if (ms / (1000 * 60 * 60 * 24) > 30) {`

#### Question:
Live coding exercise:
1) Create a Date object in which you specify only the month, date, and year.
2) In an alert display the hours, minutes, and seconds of the object. (They should all be 0.) Separate them with spaces.an alert that displays the current year.

#### Answer:
{% highlight javascript %}

var date = new Date("February 14, 1990");
alert(date.getHours() + " " + date.getMinutes() + " " + date.getSeconds());

{% endhighlight %}

#### Question:
Live coding exercise:
1) Create a Date object for the end of the month in which you're doing this exercise.
2) In a single statement display an alert that gives the number of days for that date since the reference date of January 1, 1970. Round it down to an integer.

#### Answer:
{% highlight javascript %}

var ticks = new Date("February 25, 2017").getTime();
alert(Math.floor(ticks / (1000 * 60 * 60 * 24)));

{% endhighlight %}
