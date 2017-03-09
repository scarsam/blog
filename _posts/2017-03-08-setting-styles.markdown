---
layout: posts
title:  "Setting styles"
tags: Javascript
---

#### Question:
The statement sets the element's font size at 24 pixels. Fill in the blank.
`document.getElementById(e)_____________________`

#### Answer:
`document.getElementById(e).style.fontSize = "24px";

#### Question:
The statement floats the image right. Fill in the blank.
`document.getElementById("pic1")__________________`

#### Answer:
`document.getElementById("pic1").style.cssFloat = "right";`

#### Question:
The statement makes a div with the id "d1" that was previously invisible, visible. Code it, assigning "visible".

#### Answer:
`document.getElementById("d1").style.visibility = "visible";`

#### Question:
The statement gives an element with the id "e12" a top margin of 10 pixels and a bottom margin of 20 pixels. Code it.

#### Answer:
`document.getElementById("e12").style.margin = "10px 0 20px 0";`

#### Question:
Assign an element with the id "pic1" to the variable p, which hasn't been declared beforehand. Hide it.

#### Answer:
{% highlight javascript %}

var p = document.getElementById("pic1");
p.style.visibility = "hidden";

{% endhighlight %}

#### Question:
Assign a heading with the id "head9" to the variable h, which hasn't been declared beforehand. Give it a size of 2em.

#### Answer:
{% highlight javascript %}

var h = document.getElementById("head9");
h.style.fontSize = "2em";

{% endhighlight %}

#### Question:
The element has been assigned to a variable. A font family has been assigned to a second variable. Using the two variables and the property name "fontFamily" assign the font family to the element. Make up the variables.

#### Answer:
`e.style.fontFamily = serifFamily;`

#### Question:
The element has been assigned to a variable. Using the property name "borderColor" assign a 6-character hex color (lower-case) to the element. Make up the variable.

#### Answer:
`e.style.borderColor = "#2a9c3b";`

#### Question:
The element has been assigned to a variable. Using the property name backgroundColor, assign the element's background color, styled inline, to a second variable, which hasn't been declared beforehand.

#### Answer:
`var bg = div7.style.backgroundColor;`

#### Question:
Live coding exercise:
1) When the user mouses over the paragraph, it changes size. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<p id="p1" onMouseover="chgSize();">
This could be bigger.
</p>

<script>

CODE THE FUNCTION HERE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<p id="p1" onMouseover="chgSize();">
This could be bigger.
</p>

<script>

function chgSize() {
  var p = document.getElementById("p1");
  p.style.fontSize = "2em";
}

</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks on the picture, it acquires a thick solid red border. "border" is the name of the style property. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<img src="janice-after.jpg" id="jan" onClick="makeBorder();">

<script>

CODE THE FUNCTION HERE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<img src="janice-after.jpg" id="jan" onClick="makeBorder();">

<script>
function makeBorder() {
  var month = document.getElementById("jan");
  month.style.border = "thick solid red";
}
</script>

{% endhighlight %}
