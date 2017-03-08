---
layout: posts
title:  "Setting field values"
tags: Javascript
---

#### Question:
Place some text in a field. Make up an id for the field.

#### Answer:
`document.getElementById("age").value = "21";`

#### Question:
Place some text represented by a variable of your choice in a field. Make up an id for the field.

#### Answer:
`document.getElementById("age").value = defaultAge;`

#### Question:
Clear a field. Make up its id.

#### Answer:
`document.getElementById("age").value = "";`

#### Question:
`Create a text field with the id "age"`

#### Answer:
`<input type="text" id="age">`

#### Question:
Place the concatenation of two variables in a text field. Make up the field's id.

#### Answer:
`document.getElementById("hello").value = dance + moon;`

#### Question:
Place a text value in a field whose id is stored in a variable. Make up the variable.

#### Answer:
`document.getElementById(hello).value = "myText";`

#### Question:
Place the value found in one field into another field. Make up the ids.

#### Answer:
`document.getElementById("field1").value =
 document.getElementById("field2").value;`

#### Question:
If a field is empty, fill it with a string. Make up its id.

#### Answer:
{% highlight javascript %}

if (document.getElementById("lastName").value === "") {
  document.getElementById("lastName").value = "Doe";
}

{% endhighlight %}

#### Question:
If the variable married is false, place the value "available" in the field with the id "status"

#### Answer:
{% highlight javascript %}

if (married === false) {
  document.getElementById("status").value = "available";
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks in the field, the function fills the field with a value. Code the function. Don't change any of my code. Don't copy and paste the answer. If you do, it may not work.

{% highlight javascript %}

Click in the field:<br>
<input type="text" id="f" onFocus="fill();">

<script>

CODE THE FUNCTION IN THIS SPACE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

Click in the field:<br>
<input type="text" id="f" onFocus="fill();">

<script>

function fill() {
  document.getElementById("f").value = "hello";
}

</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user enters "no" in the field with an id of "married," a function is called that fills in the field with an id of "status" with the value "available". Code the function. Don't change any of my code.

{% highlight javascript %}

Enter no in the Married field. Then click in the Available field.<br><br>

Married?:<br>
<input type="text" id="married" onBlur="fillStatus();"><br>
Available?:<br>
<input type="text" id="status" value="to be determined">

<script>


CODE THE FUNCTION IN THIS SPACE


</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

Enter no in the Married field. Then click in the Available field.<br><br>

Married?:<br>
<input type="text" id="married" onBlur="fillStatus();"><br>
Available?:<br>
<input type="text" id="status" value="to be determined">

<script>
function fillStatus() {
  if (document.getElementById("married").value === "no") {
    document.getElementById("status").value = "available";
  }
}
</script>

{% endhighlight %}
