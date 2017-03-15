---
layout: posts
title:  "The DOM: Parents and children"
tags: Javascript
---

#### Question:
A node is the _____ of the node that encloses it.

#### Answer:
child

#### Question:
A node is the _____ of a node that it encloses.

#### Answer:
parent

#### Question:
Nodes that share the same parent are ________.

#### Answer:
siblings

#### Question:
In the bare-bones web page we've been using as an example, what is the only child of the document?

#### Answer:
`html`

#### Question:
What is the parent of the body?

#### Answer:
`html`

#### Question:
What node has no parent?

#### Answer:
document

#### Question:
What type of node has no children?

#### Answer:
text

#### Question:
In this markup, the text node that begins "So many nodes..." is the child of ______.
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
In this markup, the parent of "Age-old problem" is ____.
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
