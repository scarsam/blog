---
layout: posts
title:  "Math Expressions: eliminating ambiguity"
tags: Javascript
---

#### Question:
`calculatedNum = 2 + (2 * 6);`
What is the value of `calculatedNum`?

#### Answer:
The priority order is first focus on the parentheses.
2 * 6 = 12
12 + 2 = 14
The value is `14`.

#### Question:
`calculatedNum = (2 + 2) * 6;`
What is the value of `calculatedNum`?

#### Answer:
The priority order is first focus on the parentheses.
2 + 2 = 4
4 * 6 = 24
The value is `24`.

#### Question:
`calculatedNum = (2 + 2) * (4 + 2);`
What is the value of `calculatedNum`?

#### Answer:
The priority order is first focus on the parentheses.
2 + 2 = 4
4 + 2 = 6
4 * 6 = 24
The value is `24`.

#### Question:
`calculatedNum = ((2 + 2) * 4) + 2;`
What is the value of `calculatedNum`?

#### Answer:
2 + 2 = 4
4 * 4 = 16
16 + 2 = 18
The value is `18`.

#### Question:
Write a statement that assigns to `calculatedNum` the result of 2 + 2 * 4 + 10, clarified with parentheses, producing 20. The variable hasn't been declared beforehand.

#### Answer:
`var calculatedNum = 2 + (2 * 4) + 10;`

#### Question:
Write a statement that assigns to `pressure` the result of 4 / 2 * 4, clarified with parentheses, producing .5. The variable hasn't been declared beforehand.

#### Answer:
`var pressure` = 4 / (2 * 4);`

#### Question:
Write a statement that assigns to `pressure` the result of 4 / 2 * 4, clarified with parentheses, producing 8. The variable hasn't been declared beforehand.

#### Answer:
`var pressure = (4 / 2) * 4;`

#### Question:
Write a statement that assigns to a variable the result of adding two variables together and then afterward multiplying the result of the addition by another variable. The first variable has been declared beforehand.

#### Answer:
`cost = (foodCost + laborCost) * multiplier;`

#### Question:
Write a statement that assigns to a variable the result of 4 / 2 * 4 - 1, clarified with parentheses, producing -.5. The variable hasn't been declared beforehand.

#### Answer:
var x = (4 / (2 * 4)) - 1;

#### Question:
Live coding exercise:
1) Assign to a variable the result of a math expression that requires a set of parentheses. 
2) Display an alert, specifying the variable as the message.

#### Answer:
{% highlight javascript %}
	var test = (2 + 2) * 2;
	alert(test);
{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign numbers to three variables.
2) Display an alert, specifying as the message a math expression of your choosing that uses the three variables and requires parentheses. The alert will display the result of the calculation.

#### Answer:
{% highlight javascript %}
	var test = 2;
	var fest = 3;
	var hello = 4;
	alert((test + fest) * hello);
{% endhighlight %}

#### Question:
Live coding exercise:
1) Assign a number value to a variable.
2) Increment the variable using minimal code while assigning its incremented value to a second variable. Both variables wind up with the same value.
3) Display the value of the second variable in an alert.

#### Answer:
{% highlight javascript %}
	var test = 10;
	var fest = ++test;
	alert(fest);
{% endhighlight %}