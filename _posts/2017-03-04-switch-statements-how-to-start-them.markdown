---
layout: posts
title:  "switch statements: how to start them"
tags: Javascript
---

#### Question:
The more conditions you need to test, the more you need to use a ______ statement.

#### Answer:
switch

#### Question:
Wherever you could use an ________ statement and its variations, you can use a switch statement.

#### Answer:
if

#### Question:
A switch statement begins with the keyword _________.

#### Answer:
switch

#### Question:
The second keyword used in a switch statement is _______.

#### Answer:
case

#### Question:
Code the first line of a switch statement.

#### Answer:
`switch(var) {`

#### Question:
Code the first two lines of a switch statement that tests whether a particular string of your choice has been assigned to a particular variable of your choice.

#### Answer:
{% highlight javascript %}

switch(country) {
case "Portugal" :

{% endhighlight %}

#### Question:
Code the second line of a switch statement that tests for a number.

#### Answer:
`case 12 :`

#### Question:
Code the second line of a switch statement that tests for a Boolean value.

#### Answer:
`case true :`

#### Question:
Code the first two lines of a switch statement. It tests for a Boolean value.

#### Answer:
{% highlight javascript %}

switch(boolean) {
case true :

{% endhighlight %}

#### Question:
Live coding exercise:
1) Insert the missing line of code in the space I've provided after the first line. Leave my code as-is except for filling in that space. The correct code displays an alert with the message "You won"

{% highlight javascript %}

var win = true;

case true :
  alert("You won");
  break;
case false :
  alert("You lost");
  break;
}

{% endhighlight %}


#### Answer:
{% highlight javascript %}

var win = true;
switch(win) {
case true :
  alert("You won");
  break;
case false :
  alert("You lost");
  break;
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) Insert the missing two lines of code in the spaces I've provided beneath the first two lines. (Leave my code as-is except for filling in those spaces.) The missing test is for the ZIP code 10001. If your code runs correctly, an alert will display saying "The city is Chicago"

{% highlight javascript %}

var ZIP = "60290";
var city;


  city = "New York";
  break;
case "60290" :
  city = "Chicago";
  break;
case "90001" :
  city = "Los Angeles";
  break;
}
alert("The city is " + city);

{% endhighlight %}

#### Answer:
{% highlight javascript %}

var ZIP = "60290";
var city;
switch(ZIP) {
case "10001" :
  city = "New York";
  break;
case "60290" :
  city = "Chicago";
  break;
case "90001" :
  city = "Los Angeles";
  break;
}
alert("The city is " + city);

{% endhighlight %}
