---
layout: posts
title:  "Form validation: radio buttons"
tags: Javascript
---

#### Question:
When validating a group of buttons, you target the group by specifying the...

#### Answer:
name

#### Question:
Fill in the blank.
`var targetButtons = ______________________("r2");`

#### Answer:
`var targetButtons = document.getElementByName("r2");`

#### Question:
Has the user clicked this button? Fill in the blank.
`if (targetButtons[i]._______) {`

#### Answer:
`if (targetButtons[i].checked) {`

#### Question:
If the loop finds no button has been clicked, what is the first thing that happens? Answer with one word.

#### Answer:
alert

#### Question:
Write the opening tag for a form that executes a validation function, val, when the form is submitted, passing the name "bGroup" to the function.

#### Answer:
`<form onSubmit="return val('bGroup');">`

#### Question:
Assign the group of buttons whose name is "ra" to the variable bRegions, which hasn't been declared beforehand.

#### Answer:
`var bRegions = document.getElementsByName("ra");`

#### Question:
Code the first line of an if statement within a for loop that tests whether the current button in the group bGroup has been clicked. Use the most common counter. Don't indent.

#### Answer:
`if (bGroup[i].checked) {`

#### Question:
Code the next 4 lines.
{% highlight javascript %}
function validateRadios() {
  var radios = document.getElementsByName("r1");
  for (var i = 0; i < radios.length; i++)	{
{% endhighlight %}

#### Answer:
{% highlight javascript %}
function validateRadios() {
  var radios = document.getElementsByName("r1");
  for (var i = 0; i < radios.length; i++)	{
    if(radios[i].checked) {
      return true;
    }
  }
{% endhighlight %}
#### Question:
Code the first 3 lines of a function with no parameters that validates a group of buttons.

#### Answer:
{% highlight javascript %}
function validateRadios() {
  var radios = document.getElementsByName("r1");
  for (var i = 0; i < radios.length; i++) {
{% endhighlight %}
