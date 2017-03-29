---
layout: posts
title:  "Form validation: ZIP codes"
tags: Javascript
---

#### Question:
The number of characters in the field will be assigned to the variable. Fill in the blank.
`var target = document.getElementById("zip");`
`var numOfCharacters = target.value_________;`

#### Answer:
`.length`

#### Question:
The number of characters in the field will be assigned to the variable. Fill in the blank.
`var target = document.getElementById("zip");`
`var numOfCharacters = target._________.length;`

#### Answer:
`value`

#### Question:
The statement attempts to convert the string character to an integer and assign it to the variable. Fill in the blank.
`var num = _________(stringCharacter);`

#### Answer:
`var num = parseInt(stringCharacter);`

#### Question:
If the loop finds no This is the first line of an if statement that tests whether the value of zipChar is a non-number. Fill in the blank.
`if (________(zipChar)) {`

#### Answer:
`if (isNaN(zipChar)) {`

#### Question:
Assign the number of characters in the field with the ID "postalCode" to the variable `chars`, which hasn't been declared beforehand.

#### Answer:
`var chars = document.getElementById("postalCode").value.length;`

#### Question:
Code the first line of an if statement that tests whether thisChar is a non-number.

#### Answer:
`if (isNaN(thisChar)) {`

#### Question:
The field has been assigned to the variable zipField. Assign the number of characters in the field to the variable numChars, which hasn't been declared beforehand.

#### Answer:
`var numChars = zipField.value.length;`

#### Question:
The function checks whether the user's entry is fewer than five characters. If so, it flashes an alert and cancels the submission. These lines have already been coded.
{% highlight javascript %}
function validateZIP() {
  var numChars = document.getElementById("zip").value.length;
{% endhighlight %}
Code the next 5 lines.

#### Answer:
{% highlight javascript %}
function validateZIP() {
  var numChars = document.getElementById("zip").value.length;
  if (numChars < 5) {
    alert("warning");
    return false;
  }
{% endhighlight %}

#### Question:
The function checks a ZIP code field for a non-number. These lines have already been coded.
`var num;`
`for (var i = 0; i <= 4; i++) {`
Code the next two lines. Start by attempting to convert the current character, a character within the string represented by str, to an integer, assigning it to `num`. Then begin an if statement that tests whether it's a non-number.

#### Answer:
{% highlight javascript %}
var num;
for (var i = 0; i <= 4; i++) {
  num = parseInt(str[i])
  if (isNaN(num)) { 
{% endhighlight %}
