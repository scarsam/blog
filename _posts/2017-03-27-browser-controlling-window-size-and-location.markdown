---
layout: posts
title:  "Browser control: Controlling the window's size and location"
tags: Javascript
---

#### Question:
What is the second parameter of the window.open method? Answer with one word.

#### Answer:
name

#### Question:
There's an illegal character in this statement. Type it.
`var newWin = window.open("", "My Window");`

#### Answer:
space in the name

#### Question:
In size and position parameters, what do the numbers represent? Answer with one word.

#### Answer:
pixels

#### Question:
What is the minimum number of pixels in the width and height parameters? Answer with a numeral.

#### Answer:
100px

#### Question:
Fill in the two size parameters, starting with width.
`var newWin = window.open("", "", ______________);`

#### Answer:
`var newWin = window.open("", "", "width=100, height=100");`

#### Question:
Using a variable that hasn't been declared beforehand, open a window. Assigning blank URL and name parameters, specify window size and position in this order: size across, size up and down, distance from the side, and distance from the top.

#### Answer:
`var w = window.open("", "", "width=300,height=200,left=25,top=25");`

#### Question:
Open a new window with an html page that shares the same host and subdirectory as the original page, and specify a size, with the width first.

#### Answer:
`var pop = window.open("bio.html", "", "width=300,height=150");`

#### Question:
Open a document, specifying boo.com as the URL. Also, give the window a name.

#### Answer:
`var pop = window.open("http://www.boo.com", "Boo");`

#### Question:
Open a window, specifying x.html as the first parameter and any name as the second parameter. Make it 500 pixels wide and 300 pixels high. Set it in 50 pixels and down 50 pixels.

#### Answer:
`var x = window.open("x.html", "name", "width=500,height=300,left=50,top=50");`
