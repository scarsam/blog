---
layout: posts
title:  "Form validation: text fields"
tags: Javascript
---

#### Question:
If I plan to validate this field, targeting it in the most common way, what's missing? Answer with one word, in upper-case.
`<input type="text">`

#### Answer:
`ID`

#### Question:
In the examples I'm using, what keyword triggers the function that validates the form?

#### Answer:
onSubmit

#### Question:
What property of the field value tells you whether the field has something in it or not?

#### Answer:
length

#### Question:
If I plan to validate this form, what's missing from this markup?
`<form onSubmit="validateMe();">`

#### Answer:
return

#### Question:
Write the opening tag for a form whose id is "frm1" that executes a validation function, val, when the form is submitted.

#### Answer:
`<form id="frm1" onSubmit="return val();">`

#### Question:
Code the first line of an if statement that tests whether the field with an ID of f1 is empty.

#### Answer:
`if (document.getElementById("f1").value.length === 0) {`

#### Question:
The code checks for an empty field. Fill in the blank.
{% highlight javascript %}
var targetField = document.getElementById("f1");
if __________________________________________
  alert("Please enter your name");
  return false;
}
{% endhighlight %}

#### Answer:
`(targetField.value.length === 0) {`

#### Question:
This is the first line of code that displays an alert if the field is empty, and cancels the form submission. Write 4 more lines to complete it.
`var targetField = document.getElementById("f1");`

#### Answer:
{% highlight javascript %}
if (targetField.value.length === 0) {
  alert("field is empty");
  return false;
}
{% endhighlight %}

#### Question:
Assign the target field with an ID of "f1" to a variable. Then code 4 more lines to display an alert if the field is empty, and cancel the submission.

#### Answer:
{% highlight javascript %}
var targetField = document.getElementById("f1");
if (targetField.value.length === 0) {
  alert("Empty field");
  return false;
}
{% endhighlight %}
