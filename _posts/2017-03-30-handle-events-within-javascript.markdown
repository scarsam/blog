---
layout: posts
title:  "Handle events within JavaScript"
tags: Javascript
---

#### Question:
When the button represented by `b1` is clicked, the function is called. Fill in the blank.
`b1.______ = doSomething;`

#### Answer:
`b1.onclick = doSomething;`

#### Question:
When the button represented by `b1` is clicked, the function is called. Fill in the blank.
`___.onclick = doSomething;`

#### Answer:
`b1.onclick = doSomething;`

#### Question:
When the button represented by `b1` is clicked, the function `doSomething` is called. Fill in the blank.
`b1.onclick = ________;`

#### Answer:
`b1.onclick = doSomething;`

#### Question:
In a single statement convert this markup to scripted event-handling.
`<input type="button" value="Click to be greeted" id="b1" onClick="sayHi();">`

#### Answer:
`document.getElementById("b1").onclick = sayHi;`

#### Question:
When the button represented by `b1` is clicked, the function `calc` is called.

#### Answer:
`b1.onclick = calc;`

#### Question:
When the user clicks out of a field represented by f1, a function with a name of your choice executes.

#### Answer:
`f1.onblur = hello;`

#### Question:
In a single statement conver this markup to scripted event-handling.
`<a href="Javascript:void(0)" onClick="doIt()" id="lnk">Click</a>`

#### Answer:
`document.getElementById("lnk").onclick = doIt`

#### Question:
Code an event handler that calls the function when the button is clicked. Don't change any of my code. Code the event handler in the space under the `<script>` tag.
{% highlight javascript %}
<input type="button" value="Click" id="b">
<script>

function message() {
  alert("You clicked!");
}
</script>
{% endhighlight %}

#### Answer:
{% highlight javascript %}
<input type="button" value="Click" id="b">
<script>
document.getElementById("b").onclick = message;
function message() {
  alert("You clicked!");
}
</script>
{% endhighlight %}

#### Question:
Display the image janice-before.jpg. When the image is moused over, call the function. Don't change any of my code. Code the markup in the space above the `<script>` tag. Code the event handler in the space beneath the `<script>` tag.
{% highlight javascript %}

<script>

function swap() {
  document.getElementById("pic").src = "janice-after.jpg";
}
</script>
{% endhighlight %}


#### Answer:
{% highlight javascript %}
<img src="janice-before.jpg" id="pic">
<script>
document.getElementById("pic").onmouseover = swap;
function swap() {
  document.getElementById("pic").src = "janice-after.jpg";
}
</script>
{% endhighlight %}
