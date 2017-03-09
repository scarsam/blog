---
layout: posts
title:  "Target all elements by tag name"
tags: Javascript
---

#### Question:
The statement makes a collection of all the divs in the document. Fill in the blank.
`var divs = document______________("div");`

#### Answer:
`var divs = document.getElementsByTagName("div");`

#### Question:
The statement assigns the first item of imgLst to firstPic. Fill in the blank.
`var firstPic = __________`

#### Answer:
`var firstPic = imgLst[0];`

#### Question:
The statement assigns the number of items in listOfParagraphs to numbrInList. Fill in the blank.
`var numbrInList = __________________`

#### Answer:
`var numbrInList = listOfParagraphs.length;`

#### Question:
The statement assigns a collection of h1 headings in a document to the variable bigHeads, which hasn't been declared beforehand. Code it.

#### Answer:
`var bigHeads = document.getElementsByTagName("h1");`

#### Question:
Assign a collection of the images in the document to the variable pics, which hasn't been declared beforehand.

#### Answer:
`var pics = document.getElementsByTagName("img");`

#### Question:
In a single statement assign the number of paragraphs in the document to the variable numbrPgraphs, which hasn't been declared beforehand.

#### Answer:
`var numbrPgraphs = document.getElementsByTagName("p").length;`

#### Question:
Assign the links in the document to a variable that hasn't been declared beforehand.

#### Answer:
`var lnk = document.getElementsByTagName("a");`

#### Question:
Assign the third element in the collection represented by eList to the variable thirdE, which hasn't been declared beforehand.

#### Answer:
`var thirdE = eList[2];`

#### Question:
Code a for loop that cycles through the first 3 elements of a list, which has been assigned to a variable, and assign a class to each of them. Use the most common specifications for the loop.

#### Answer:
{% highlight javascript %}

for (var i = 0; i <= 2; i++) {
  eList[i].className = "indented";
}

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks the button, the text of the second paragraph—"This bed is too big"—displays in an alert. Code the statement that creates a list of paragraphs and assigns it to the variable pgraphs.

{% highlight javascript %}

<p>This bed is too small.</p>
<p>This bed is too big.</p>
<p>This bed is just right.</p>
<input type="button" value="Click to see 2nd paragraph" onClick="displayPgraph();">

<script>
function displayPgraph() {
  CREATE A LIST OF THE PARAGRAPHS AND ASSIGN IT TO pgraphs HERE
  alert(pgraphs[1].innerHTML);
}
</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<p>This bed is too small.</p>
<p>This bed is too big.</p>
<p>This bed is just right.</p>
<input type="button" value="Click to see 2nd paragraph" onClick="displayPgraph();">

<script>
function displayPgraph() {
  var pgraphs = document.getElementsByTagName("p");
  alert(pgraphs[1].innerHTML);
}
</script>

{% endhighlight %}

#### Question:
Live coding exercise:
1) When the user clicks the button, the text of the last paragraph—"This bed is just right"—displays in an alert. Code the statement that displays the alert, specifying the last item in the element list as the location of the text.

{% highlight javascript %}

<p>This bed is too small.</p>
<p>This bed is too big.</p>
<p>This bed is just right.</p>
<input type="button" value="Click to see last paragraph" onClick="displayPgraph();">

<script>
function displayPgraph() {
  var pgraphs = document.getElementsByTagName("p");
  CODE THE STATEMENT THAT DISPLAYS THE ALERT HERE
}
</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<p>This bed is too small.</p>
<p>This bed is too big.</p>
<p>This bed is just right.</p>
<input type="button" value="Click to see last paragraph" onClick="displayPgraph();">

<script>
function displayPgraph() {
  var pgraphs = document.getElementsByTagName("p");
  alert(pgraphs[2].innerHTML);
}
</script>

{% endhighlight %}
