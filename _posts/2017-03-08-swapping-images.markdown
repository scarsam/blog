---
layout: posts
title:  "Swapping images"
tags: Javascript
---

#### Question:
The existing image is replaced by "after.png". Fill in the blank.
`______________("pic1").src = "after.png";`

#### Answer:
`document.getElementById("pic1").src = "after.png";`

#### Question:
The existing image is replaced by "after.png". Fill in the blank.
`document.getElementById("pic1")________________`

#### Answer:
`document.getElementById("pic1").src = "after.png";`

#### Question:
When the user clicks on the image, a function is called. Write the markup in this order: source, id, event handler.

#### Answer:
`<img src="cat.png" id="cat" onClick="clickCat();">`

#### Question:
The first line of the function is...
`function swap(picId, nextPic) {`
The function substitutes the image represented by `nextPic` for the original image that has an id represented by `picId`. Code the line that makes the swap. Include the indent.

#### Answer:
`  document.getElementById(picId).src = nextPic;`

#### Question:
Code the line of the function that swaps out an image with the id "pic1" and substitutes the image "ant.png". Don't indent it.

#### Answer:
`document.getElementById("pic1").src = "ant.png";`

#### Question:
Write the markup for an image with an id and an onFocus event handler that calls a function. Write in this order: source, id, event handler.

#### Answer:
`<img src="cat.png" id="cat" onFocus="catFunc();">`

#### Question:
Code the line of a function that swaps an image. Don't indent.

#### Answer:
`document.getElementById("pic1").src = "field.jpg";`

#### Question:
Write the markup for an image. When the user clicks on it, a function is called. The markup passes the id and the image to insert as arguments, in that order. Write in this order: source, id, event handler.

#### Answer:
`<img src="bee.png" id="insect" onClick="newPic(id, 'ant.png');">`

#### Question:
Code a function that takes the image id and the new image that replaces the old image as parameters and inserts the new image.

#### Answer:
{% highlight javascript %}

function changePic(picId, newPic) {
  document.getElementById(picId).src = newPic;
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks on the picture, it is replaced by janice-after.jpg. Don't change any of my code. Don't copy and paste. It may not work.

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
  document.getElementById("i0").src = "janice-after.jpg"
}

</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks on the picture, it is replaced by janice-after.jpg. The function call passes two arguments to the function, which uses them in the image swap. Don't change any of my code. Don't copy and paste. It may not work.

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
function swap(pickId, img) {
  document.getElementById(pickId).src = img;
}
</script>

{% endhighlight %}
