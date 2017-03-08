---
layout: posts
title:  "Events: button"
tags: Javascript
---

#### Question:
The code creates a button that, when clicked, calls a function. Fill in the blank.
`_____________ value="Submit" onClick="myFunc();">`

#### Answer:
`<input type="button"`

#### Question:
The code creates a button that says "Click". Fill in the blank.
`<input type="button" _________ onClick="myFunc();">`

#### Answer:
`value="Click"`

#### Question:
The code creates a button that, when clicked, calls the function myFunc. Fill in the blank.
`<input type="button" value="Click" ______________`

#### Answer:
`onClick="myFunc();">`

#### Question:
The code displays an image, but.gif, that, when clicked, calls the function myFunc. Fill in the blank.
`_______________ onClick="myFunc();">`

#### Answer:
`<img src="but.gif"`

#### Question:
When the button, which says "Say hi", is clicked, an alert displays saying "Hi". Complete the code.
`<input type="button"`

#### Answer:
`<input type="button" value="Say hi" onClick="alert('Hi');">`

#### Question:
When the button, which says "Click", is clicked, the function doIt executes. Code it.

#### Answer:
`<input type="button" value="Click" onClick="doIt();">`

#### Question:
When the image click.png is clicked, an alert displays saying, "You clicked the pic" Fill in the blank.
`________________ onClick="alert('You clicked the pic');">`

#### Answer:
`img src="click.png" onClick="alert('You clicked the pic');">`

#### Question:
When the image click.png is clicked, an alert displays saying, "You clicked the pic" Code it.

#### Answer:
`<img src="click.png" onClick="alert('You clicked the pic');">`

#### Question:
When the image, pic.gif, is clicked, the function doIt executes. Code it.

#### Answer:
`<img src="pic.gif" onClick="doIt();">`

#### Question:
Live coding exercise:
1) Code a button that, when clicked, displays an alert.

#### Answer:
{% highlight javascript %}

<input type="button" value="Click me" onClick="alert('Clicking the button aye');">

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a button that, when clicked, calls the function. Don't change my code. Add your code below it.

{% highlight javascript %}

<script>
function greet() {
  alert("Hello world!");
}
</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<script>
function greet() {
  alert("Hello world!");
}
</script>
<input type="button" value="Click me" onClick="greet();">

{% endhighlight %}
