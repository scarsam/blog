---
layout: posts
title:  "Events: link"
tags: Javascript
---

#### Question:
Fill in the blank.
`______"JavaScript:void(0)" onClick="greet();">Get greeting</a>`

#### Answer:
<a href=

#### Question:
Fill in the blank. Use any text you like.
`<a href="JavaScript:void(0)" onClick="find();">_________`

#### Answer:
hello</a>

#### Question:
Type the 3 characters that are missing. (They aren't necessarily consecutive.)
`<a href="JavaScript:void(0)" onClick popup('Hi');>Click</a>`

#### Answer:
=""

#### Question:
What is the keyword that tells the browser to watch for a click on a link?

#### Answer:
onClick

#### Question:
To complete the code for this link that triggers an event when it's clicked, fill in the blank.
`<a href="JavaScript:void(0)" _________"alert('Hi');">Click</a>`

#### Answer:
`onClick=`

#### Question:
To complete the code for this link that triggers an event when it's clicked, fill in the blank, using the preferred approach (no #).
`<a href=_____________ onClick="alert('Hi');">Click</a>`

#### Answer:
`"JavaScript:void(0)"`

#### Question:
Using the preferred approach (no #), code a link that triggers an event—but stop coding after the second equal sign.

#### Answer:
`<a href="JavaScript:void(0)" onClick= `

#### Question:
Using the preferred approach (no #), write the markup for a link, that says anything you like, that, when clicked, calls a function. The name of the function is also up to you.

#### Answer:
`<a href="JavaScript:void(0)" onClick="myFunc();">Click</a>`

#### Question:
Live coding exercise:
1) Code a link that, when clicked, displays an alert.

#### Answer:
{% highlight javascript %}

<a href="JavaScript:void(0)" onClick="alert('hello');">Hello link</a>

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a link that, when clicked, calls the function. Don't change my code. Add your code below it.

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
<a href="JavaScript:void(0)" onClick="greet();">Hello world</a>

{% endhighlight %}
