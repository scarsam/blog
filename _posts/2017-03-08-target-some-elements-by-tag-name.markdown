---
layout: posts
title:  "Target some elements by tag name"
tags: Javascript
---

#### Question:
The statement makes a collection of all the paragraphs in the div represented by the variable contentDiv and assigns the collection to pgraphs. Fill in the blank.
`var pgraphs = ________getElementsByTagName("p");`

#### Answer:
`var pgraphs = contentDiv.getElementsByTagName("p");`

#### Question:
The statement makes a collection of all the images in the div represented by the variable contentDiv and assigns the collection to pics. Fill in the blank.
`var pics = _____________________________`

#### Answer:
`var pics = contentDiv.getElementsByTagName("img")`

#### Question:
If the length of the collection represented by the variable elementList is 10, how do you specify the next-to-last element in the collection?

#### Answer:
`elementList[8];`

#### Question:
Assign a list of links in the paragraph represented by the variable keyParagraph to the variable links, which hasn't been declared beforehand.

#### Answer:
`var links = keyParagraph.getElementsByTagName("a");`

#### Question:
The statement makes a list of all the paragraphs in the div represented by the variable d and assigns the list to ps, which hasn't been declared beforehand. Code it.

#### Answer:
`var ps = d.getElementsByTagName("p");`

#### Question:
The statement makes a list of all the images in the div represented by the variable d and assigns the list to pics, which hasn't been declared beforehand. Code it.

#### Answer:
`var pics = d.getElementsByTagName("img");`

#### Question:
Get a list of the items in an ordered list that has been assigned to the variable l. (That's an el, not a one.) Assign the list of items to the variable numI, which hasn't been declared beforehand.

#### Answer:
`var numI = l.getElementsByTagName("li");`

#### Question:
Get a list of the regular (non-header) cells in a table that has been assigned to the variable t. Assign the list of items to the variable cells, which hasn't been declared beforehand.

#### Answer:
`var cells = t.getElementsByTagName("td");`

#### Question:
Code a for loop that cycles through the first 3 paragraphs of a list, which has been assigned to an array of your choosing, and assign the text contents of each paragraph to an array item. Use the common loop specifications. This statement creates the array that collects the text contents:
`var contents = [];`

#### Answer:
{% highlight javascript %}

for (var i = 0; i < 3; i++) {
  contents[i] = paragraphList[i].innerHTML;
}

{% endhighlight %}

#### Question:
Live coding exercise:
When the user clicks the button, the text of the first paragraph in the div—"This bed is just right"—displays in an alert.
1) Assign the div to a variable.
2) Referring to the div variable, create a list of paragraphs within the div and assign it to the variable pgraphs.

{% highlight javascript %}

<p>This bed is too small.</p>
<p>This bed is too big.</p>
<div id="justRight">
<p>This bed is just right.</p>
<p>I'll take it.</p>
</div>
<input type="button" value="Click for satisfaction" onClick="displayPgraph();">

<script>
function displayPgraph() {
  CODE THE 2 STATEMENTS HERE

  alert(pgraphs[0].innerHTML);
}
</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<p>This bed is too small.</p>
<p>This bed is too big.</p>
<div id="justRight">
<p>This bed is just right.</p>
<p>I'll take it.</p>
</div>
<input type="button" value="Click for satisfaction" onClick="displayPgraph();">

<script>
function displayPgraph() {
  var targetDiv = document.getElementById("justRight");
  var pgraphs = targetDiv.getElementsByTagName("p");
  alert(pgraphs[0].innerHTML);
}
</script>

{% endhighlight %}

#### Question:
Live coding exercise:
When the user clicks the button, the regular cells of the table turn yellow.
1) Assign the table to a variable.
2) Referring to the table variable, make a list of the regular cells.
3) Code a for loop that colors the cells yellow.

{% highlight javascript %}

<table id="cuteness">
  <tr>
    <th>Animal</th>
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
  <tr>
    <td>Spider</td>
    <td>low</td>
  </tr>  
</table>
<input type="button" value="Click to color cells" onClick="colorCells();">

<script>
function colorCells() {
  CODE THE 2 STATEMENTS AND THE LOOP HERE




}
</script>

{% endhighlight %}

#### Answer:
{% highlight javascript %}

<table id="cuteness">
  <tr>
    <th>Animal</th>
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
  <tr>
    <td>Spider</td>
    <td>low</td>
  </tr>  
</table>
<input type="button" value="Click to color cells" onClick="colorCells();">

<script>
function colorCells() {
  var tableVar = document.getElementById("cuteness");
  var cells = tableVar.getElementsByTagName("td");
  for (var i = 0; i < cells.length; i++) {
    cells[i].style.backgroundColor = "yellow";
  }
}
</script>

{% endhighlight %}
