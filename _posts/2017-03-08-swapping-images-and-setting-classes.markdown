---
layout: posts
title:  "Swapping images and setting classes"
tags: Javascript
---

#### Question:
Assign an element with the id "p1" to the variable pgraph, which hasn't been declared beforehand.

#### Answer:
`var pgraph = document.getElementById("p1");`

#### Question:
The element has been assigned to the variable pgraph. Assign its class to the variable pClass, which hasn't been declared beforehand.

#### Answer:
`var pClass = pgraph.className;`

#### Question:
Assign the source "pic2.gif" to the element represented by the variable classPic.

#### Answer:
`classPic.src = "pic2.gif";`

#### Question:
To any classes that are already assigned to the element represented by the variable e, add the class "special".

#### Answer:
`e.className += " special";`

#### Question:
Assign an element with the id "pic1" to the variable p, which hasn't been declared beforehand. Assign as a source the image "ant.png".

#### Answer:
{% highlight javascript %}

var p = document.getElementById("pic1");
p.src = "ant.png";

{% endhighlight %}

#### Question:
Assign an element with the id "head9" to the variable h, which hasn't been declared beforehand. Assign the element's class to the variable c, which hasn't been declared beforehand.

#### Answer:
{% highlight javascript %}

var h = document.getElementById("head9");
var c = h.className;

{% endhighlight %}

#### Question:
Assign an element to a variable that hasn't been declared beforehand. Using the variable, assign a new class to the element.

#### Answer:
{% highlight javascript %}

var pic = document.getElementById("pic1");
pic.className = "floatLeft";

{% endhighlight %}

#### Question:
Using variables to represent the element's id and its new class, assign an element to a variable that hasn't been declared beforehand and then a new class to the element.

#### Answer:
{% highlight javascript %}

var e = document.getElementById(eId);
e.className = newClass;

{% endhighlight %}

#### Question:
Code a function that assigns a new image source to an image element. The ID of the image element is the first parameter. The path to the image source is the second parameter. First assign the image element to a variable that hasn't been declared beforehand. Then assign the new image path to that variable.

#### Answer:
{% highlight javascript %}

function changePic(picId, newPic) {
  var pic = document.getElementById(picId);
  pic.src = newPic;
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks on the picture, it is replaced by janice-after.jpg. When coding the function, assign the element to a variable. Use the variable to make the swap. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<img src="janice-before.jpg" id="i0" onClick="swap();">

<script>

CODE THE FUNCTION HERE


</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<img src="janice-before.jpg" id="i0" onClick="swap();">

<script>

function swap() {
  var img = document.getElementById("i0");
  img.src = "janice-after.jpg";
}

</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks on the picture, it is replaced by janice-after.jpg. The function call passes two arguments to the function, which uses them in the image swap. When coding the function, assign the element to a variable. Use the variable to make the swap. Don't change any of my code. Don't copy and paste. It may not work.

{% highlight javascript %}

<img src="janice-before.jpg" id="i0" onClick="swap(id,'janice-after.jpg');">

<script>

CODE THE FUNCTION HERE


</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<img src="janice-before.jpg" id="i0" onClick="swap(id,'janice-after.jpg');">

<script>

function swap(id, newImg) {
  var img = document.getElementById(id);
  img.src = newImg;
}
</script>

{% endhighlight %}
