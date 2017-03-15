---
layout: posts
title:  "The DOM: Finding children"
tags: Javascript
---

#### Question:
The target is the first child of the body, which has been assigned to the variable `b`. Fill in the blank.
`var e = b_________________`

#### Answer:
`var e = b.childNodes[0];`

#### Question:
The target is the fourth child of the second child of the body. The body has been assigned to the variable `b`. Fill in the blank.
`var e = _________________________`

#### Answer:
`var e = b.childNodes[1].childNodes[3];`

#### Question:
A div has been assigned to the variable `d`. Assign the third child of the div to the variable `p`, which hasn't been declared beforehand.

#### Answer:
`var p = d.childNodes[2];`

#### Question:
The body has been assigned to the variable b. Assuming the two divs and their children comprise the only markup and that there are no junk artifacts, what is the value of: `b.childNodes[1].childNodes[2].innerHTML`
{% highlight javascript %}
<div id="d1">
  <p>Don't tell me.</p>
  <p>Let me guess.</p>
</div>
<div id="d2">
  <p>Oh.</p>
  <p>my.</p>
  <p>God.</p>
</div>
{% endhighlight %}
Be sure to put the answer in quotes.

#### Answer:
"God."

#### Question:
The div with an id of "photos" has been assigned to the variable `divP`. The second child of the div is a paragraph. Assign its text contents to the variable `txt`, which hasn't been declared beforehand.

#### Answer:
`var txt = divP.childNodes[1].innerHTML;`

#### Question:
The div has been assigned to a variable, `d`. Assign the em element to a variable, which hasn't been declared beforehand. (Assume there are no junk artifacts.)
{% highlight javascript %}
<div id="d1">
  <p>You are <em>so</em> good-looking!</p>
</div>
{% endhighlight %}

#### Answer:
`var n = d.childNodes[0].childNodes[1];`

#### Question:
Using its id to identify it, assign an element to a variable. Assign any child of that element to another variable. Neither variable has been declared beforehand.

#### Answer:
`var e = document.getElementById("div3");`
`var c = e.childNodes[8];`

#### Question:
Fill in the blank to assign the first node of the head section to the variable.
`var x = document.___________________________`

#### Answer:
`var x = document.childNodes[0].childNodes[0].childNodes[0];`

#### Question:
The div has been assigned to the variable d. Assign the last element node of the div to a variable, which hasn't been declared beforehand. Assume the DOM has been cleaned of junk artifacts.
{% highlight javascript %}
<div id="text">
  <p>A baseball team comprises 9 players.</p>
  <p>A football team comprises 11 players.</p>
  <p>A basketball team comprises 5 players.</p>
  <p>A mule team comprises 20 players.</p>
</div>
{% endhighlight %}

#### Answer:
`var x = d.childNodes[3];`

#### Question:
Assuming that junk artifacts have been cleaned from the DOM, what is the second child of the first element node?
{% highlight javascript %}
<div>
  <h3>Age-old problem</h3>
  <p>
    So many nodes, so little time.
  </p>
</div>
{% endhighlight %}

#### Answer:
`<p>`

#### Question:
What is the parent of the first text node?
{% highlight javascript %}
<div>
  <h3>Age-old problem</h3>
  <p>
    So many nodes, so little time.
  </p>
</div>
{% endhighlight %}

#### Answer:
`<h3>`

#### Question:
What is the sibling of <h3>?
{% highlight javascript %}
<div>
  <h3>Age-old problem</h3>
  <p>
    So many nodes, so little time.
  </p>
</div>
{% endhighlight %}

#### Answer:
`<p>`

#### Question:
The children of `<html>` are ___ and ____. (Separate answers by a space.)

#### Answer:
`<head>` and `<body>`

#### Question:
Assuming this is the only content on the web page, what is the parent of `<p>`?
{% highlight javascript %}
<p>
  Not much to report.
</p>
{% endhighlight %}

#### Answer:
`<body>`

#### Question:
What siblings do you see under the first `<div>`? (Separate answers with a space.)
{% highlight javascript %}
<div>
   <p>Go Athens!</p>
   <p>Beat Carthage!</p>
   <div>
     <img src="flag.png">
   </div>
 </div>
{% endhighlight %}

#### Answer:
`<p>`, `<p>` and `<div>`

#### Question:
What is the second child of `<p>`?
  `<p>This is <em>very</em> important!</p>`

#### Answer:
`<em>`

#### Question:
What is the parent of "very"?
`<p>This is <em>very</em> important!</p>`

#### Answer:
`<em>`

#### Question:
Assuming there are no junk artifacts, what is the last child of `<ol>`?
{% highlight javascript %}
<ol>
  <li>Sleepy</li>
  <li>Grumpy</li>
  <li>Salami</li>
</ol>
{% endhighlight %}

#### Answer:
`<li>`

#### Question:
Assuming no junk artifacts, what is the second child of the first child of `<table>`?
{% highlight javascript %}
<table>
  <tr>
    <th>Animals</th>
    <th>Cuteness</th>
  </tr>
  <tr>
    <td>Kitten</td>
    <td>high</td>
  </tr>
  <tr>
    <td>Parakeet</td>
    <td>medium</td>
  </tr>
</table>
{% endhighlight %}

#### Answer:
`<th>`

#### Question:
What is the minimum number of children `<table>` must have? (Answer with a numeral.)

#### Answer:
1
