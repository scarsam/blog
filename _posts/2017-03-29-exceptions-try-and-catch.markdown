---
layout: posts
title:  "Exceptions: try and catch"
tags: Javascript
---

#### Question:
What is always paired with catch? Answer with one word.

#### Answer:
`try`

#### Question:
What is always paired with try? Answer with one word.

#### Answer:
`catch`

#### Question:
What is missing from this code? Answer with one word.
`catch() {`

#### Answer:
parameter

#### Question:
The try...catch approach is mainly useful for spotting ________. Answer with two words.

#### Answer:
undefined variables

#### Question:
Code the first line of a try block.

#### Answer:
`try {`

#### Question:
Code the first line of a catch block. The parameter is up to you.

#### Answer:
`catch(err) {`

#### Question:
Display an alert. Wrap the statement in a try block.

#### Answer:
{% highlight javascript %}
try {
  alert("Hello world!");
}
{% endhighlight %}

#### Question:
Code a catch statement that displays an alert that shows the error.

#### Answer:
{% highlight javascript %}
catch(err) {
  alert(err);
}
{% endhighlight %}

#### Question:
Code a statement that adds 2 numbers and assigns the sum to a variable that hasn't been declared beforehand. Use try...catch. If there's an error, display it in an alert.

#### Answer:
{% highlight javascript %}
try {
  var sum = 2 + 2;
}
catch(sum) {
  alert(sum);
}
{% endhighlight %}
