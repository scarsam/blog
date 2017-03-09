---
layout: posts
title:  "Manipulating images and text"
tags: Javascript
---

#### Question:
Any existing classes assigned to the paragraph with the id "paragraph1" are replaced by the class "formal". Fill in the blank.
`______________("paragraph1").className = "formal";`

#### Answer:
`document.getElementById("paragraph1").className = "formal";`

#### Question:
Any existing classes assigned to the paragraph with the id "paragraph1" are replaced with the class "formal." Fill in the blank.
`document.getElementById("paragraph1").__________ = "formal";`

#### Answer:
`document.getElementById("paragraph1").className = "formal";`

#### Question:
The class "formal" is added to any existing classes assigned to the element. Fill in the blank.
`document.getElementById("paragraph1").className __ " formal";`

#### Answer:
`document.getElementById("paragraph1").className += " formal";`

#### Question:
Enter what's missing here.
`document.getElementById("paragraph1").className += "formal";`

#### Answer:
` ` space before formal.

#### Question:
Assign the class "indent" to the div with the id "quote".

#### Answer:
`document.getElementById("quote").className = "indent";`

#### Question:
Assign the class "highlight" to the paragraph with the id "summary" while retaining any original class assignments.

#### Answer:
`document.getElementById("summary").className += " highlight";`

#### Question:
Assign a class to a div. Make up the id and class name.

#### Answer:
`document.getElementById("hello").className = "dance";`

#### Question:
Assign a class to a paragraph while preserving any original classes assigned to it. Make up the id and class name.

#### Answer:
`document.getElementById("dance").className += " hello";`

#### Question:
Code the tag for an image that, when clicked on, executes a function. Code in this order: image source, id, event handler.

#### Answer:
`<img src="cat.png" id="pic1" onClick="enlarge();">`

#### Question:
Live coding exercise:
1) When the user clicks on the sentence, it turns bold. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<style>
.black {font-weight:bold;}
</style>

<p id="p1" onClick="boldIt();">
Click this sentence.
</p>

<script>

CODE THE FUNCTION HERE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<style>
.black {font-weight:bold;}
</style>

<p id="p1" onClick="boldIt();">
Click this sentence.
</p>

<script>
function boldIt() {
  document.getElementById("p1").className = "black";
}
</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user mouses over the heading, its background turns black, but it retains its original light gray color.

{% highlight javascript %}

<style>
.pale {color:#ccc;}
.blackGround {background-color:black;}
</style>

<h1 id="head1" class="pale" onMouseover="addBackground();">
This is important.
</h1>

<script>

CODE THE FUNCTION HERE

</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<style>
.pale {color:#ccc;}
.blackGround {background-color:black;}
</style>

<h1 id="head1" class="pale" onMouseover="addBackground();">
This is important.
</h1>

<script>
function addBackground() {
  document.getElementById("head1").className += "backGround";
}
</script>

{% endhighlight %}
