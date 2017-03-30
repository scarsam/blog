---
layout: posts
title:  "Exceptions: throw"
tags: Javascript
---

#### Question:
What is the keyword that passes a value to the catch parameter?

#### Answer:
`throw`

#### Question:
In a single word, what type of value can be passed by throw?

#### Answer:
any

#### Question:
In one word, what does throw pass a value to?

#### Answer:
parameter

#### Question:
As an alternative to a value, what can follow the keyword throw? Answer with one word.

#### Answer:
variable

#### Question:
Code a throw statement that passes a string. Don't indent it.

#### Answer:
`throw "hello";`

#### Question:
Code the first line of a catch statement that handles this throw statement.
`throw "Something went wrong.";`

#### Answer:
`catch(err) {`

#### Question:
If one variable equals another, throw, passing a third variable.

#### Answer:
{% highlight javascript %}
if (a === b) {
  throw c;
}
{% endhighlight %}

#### Question:
1) Begin with try.
2) Assign the value of a to b, which has been declared beforehand.
3) If b is greater than c, throw an error, passing d.

#### Answer:
{% highlight javascript %}
try {
  b = a;
  if (b > c) {
    throw d;
  }
}
{% endhighlight %}

#### Question:
1) Begin with try.
2) Assign the value of a to b, which has been declared beforehand.
3) If the value represented by b isn't a number (isNaN(b)), throw an error, passing a string.

#### Answer:
{% highlight javascript %}
try {
  b = a;
  if (isNaN(b)) {
    throw "It's not a number.";
  }
}
{% endhighlight %}
