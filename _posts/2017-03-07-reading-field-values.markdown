---
layout: posts
title:  "Reading field values"
tags: Javascript
---

#### Question:
What is the keyword for detecting that the user has submitted a form?

#### Answer:
`onSubmit`

#### Question:
What HTML tag encloses onSubmit? Don't include the brackets in your answer.

#### Answer:
`<form></form>`

#### Question:
Fill in the blank.
`var nameEntered = ________.getElementById("nameField").value;`

#### Answer:
`document`

#### Question:
Fill in the blank.
`var email = document.____________("eField").value;`

#### Answer:
`getElementById`

#### Question:
Write the first line of an if statement. If what's in the field with the id of "pet" is "dog"....

#### Answer:
`if (document.getElementById("pet").value === "dog") {`

#### Question:
Write an opening form tag. When the form is submitted, the function chkForm is called.

#### Answer:
`<form onSubmit="chkForm();">`

#### Question:
Assign the value in a field with an id of your choice to a variable, which hasn't been declared beforehand.

#### Answer:
`var hello = document.getElementById("zeus").value;`

#### Question:
Write an opening tag for a form. When the form is submitted, a function is called. The id of a field is passed to the function. Make up the id.

#### Answer:
`<form onSubmit="myFunc('myId');">`

#### Question:
Code the first line of an if statement that tests for a text value of your choice in a field.

#### Answer:
`if (document.getElementById("state").value === "Idaho") { `

#### Question:
Live coding exercise:
1) Insert the correct line that calls the function when the form is submitted. Don't change any of my code.

{% highlight javascript %}

What is your name?<br>
REPLACE THIS LINE WITH THE CORRECT CODE
  <input type="text" id="name">
  <input type="submit" value="Submit">
</form>

<script>
function sayHi() {
  var userName = document.getElementById("name").value;
  alert("Hello, " + userName + "!");
  window.close("mywindow");
}
</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

What is your name?<br>
<form onSubmit="sayHi();">
  <input type="text" id="name">
  <input type="submit" value="Submit">
</form>

<script>
function sayHi() {
  var userName = document.getElementById("name").value;
  alert("Hello, " + userName + "!");
  window.close("mywindow");
}
</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) If the user enters "dog" an alert displays saying "Bow-wow!" Insert the correct line. Don't change any of my code.

{% highlight javascript %}

Enter dog or cat:<br>
<form onSubmit="checkPet();">
  <input type="text" id="whichPet">
  <input type="submit" value="Submit">
</form>

<script>
function checkPet() {
  REPLACE THIS LINE WITH THE CORRECT CODE
    alert("Bow-wow!");
  }  
  else {
    alert("Meow!");
  }
  window.close("mywindow");
}
</script>


{% endhighlight %}

#### Answer:
{% highlight javascript %}

Enter dog or cat:<br>
<form onSubmit="checkPet();">
  <input type="text" id="whichPet">
  <input type="submit" value="Submit">
</form>

<script>
function checkPet() {
  if (document.getElementById("whichPet").value === "dog") {  
    alert("Bow-wow!");
  }  
  else {
    alert("Meow!");
  }
  window.close("mywindow");
}
</script>

{% endhighlight %}
