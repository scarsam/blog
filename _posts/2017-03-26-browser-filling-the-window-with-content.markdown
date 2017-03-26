---
layout: posts
title:  "Browser control: Filling the window with content"
tags: Javascript
---

#### Question:
A full-size blank window will open. Complete the code.
`var greatBigWindow = ____________`

#### Answer:
`window.open();`

#### Question:
A full-size blank window will open. Complete the code. Make up the handle.
`_________________ window.open();`

#### Answer:
`var x = window.open();`

#### Question:
Close a window whose handle is `faq`

#### Answer:
`faq.close();`

#### Question:
An HTML string has been assigned to the variable content. Load the string into a window whose handle is info.

#### Answer:
`info.document.write(content);`

#### Question:
Open a blank window, giving it a name.

#### Answer:
`var pop = window.open();`

#### Question:
Open a window, loading a document that's represented by a variable.

#### Answer:
`var pop = window.open(newDocument);`

#### Question:
Open a blank window, then close it.

#### Answer:
`var pop = window.open();`
`pop.close();`

#### Question:
Open a document, loading an html file that shares the same host and subdirectory as the original document.

#### Answer:
`var pop = window.open("crackle.html");`

#### Question:
Display a paragraph with text content "Whee!" in a window that's already open, whose handle is pop.

#### Answer:
`pop.document.write("<p>Whee!</p>");`
