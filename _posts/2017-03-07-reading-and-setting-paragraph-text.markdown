---
layout: posts
title:  "Reading and setting paragraph text"
tags: Javascript
---

#### Question:
The string represented by the variable newContent is placed in the paragraph. Fill in the blank.
`document.getElementById("targetParagraph").__________ = newContent;`

#### Answer:
`document.getElementById("targetParagraph").innerHTML = newContent;`

#### Question:
Assign the contents of the div with the id "div1" to the variable txt, which hasn't been declared beforehand.

#### Answer:
`var txt = document.getElementById("div1").innerHTML;`

#### Question:
Clear a paragraph. Make up the id.

#### Answer:
`document.getElementById("dance").innerHTML = "";`

#### Question:
Place a sentence in a paragraph. Make up the id.

#### Answer:
`document.getElementById("dance").innerHTML = "hello";`

#### Question:
Place the concatenation of a string and a variable in a div. Make up an id.

#### Answer:
`document.getElementById("dance").innerHTML = "hello" + dance;`

#### Question:
Place a text value in a paragraph whose id is stored in a variable. Make up the variable.

#### Answer:
`document.getElementById(storedId).innerHTML = "212";`

#### Question:
Place the value found in a field into a paragraph. Make up the ids.

#### Answer:
`document.getElementById("dancer").innerHTML =  document.getElementById("dance").value;`

#### Question:
If a div is empty, fill it with something. Make up an id.

#### Answer:
{% highlight javascript %}

if (document.getElementById("div1").innerHTML === "") {
  document.getElementById("div1").innerHTML = "Something";
}

{% endhighlight %}

#### Question:
Place the text "This is it" in a paragraph, with the word "is" surrounded by emphasis tags. Make up an id.

#### Answer:
`document.getElementById("p1").innerHTML = "This <em>is</em> it";`

#### Question:
Live coding exercise:
1) When the user clicks the button, the contents of the paragraph display in an alert. Code the function. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<p id="p1">
This is what I'm talking about.
</p>
<input type="button" value="Click to see this text in an alert"
onClick="showAlert();">

<script>

CODE THE FUNCTION HERE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<p id="p1">
This is what I'm talking about.
</p>
<input type="button" value="Click to see this text in an alert"
onClick="showAlert();">

<script>

function showAlert() {
  var content = document.getElementById("p1").innerHTML;
  alert(content);
}

</script>


{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks the button, the answer—"4"—appears below the heading, in the paragraph with the id "p1". Code the function. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<h3>Watch for answer below.</h3>
<p id="p1">Answer will appear here.</p>
<input type="button" value="Click to see answer"
onClick="showAnswer();">

<script>

CODE THE FUNCTION HERE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<h3>Watch for answer below.</h3>
<p id="p1">Answer will appear here.</p>
<input type="button" value="Click to see answer"
onClick="showAnswer();">

<script>
function showAnswer() {
  document.getElementById("p1").innerHTML = "4";
}
</script>

{% endhighlight %}
