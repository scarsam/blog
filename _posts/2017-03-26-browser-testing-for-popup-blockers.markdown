---
layout: posts
title:  "Browser control: Testing for popup blockers"
tags: Javascript
---

#### Question:
If your popups are being blocked, whom can you appeal to for help? Answer with one word, in lower-case.

#### Answer:
user

#### Question:
If your popups are being blocked and the user is on a browser other than Internet Explorer, what is the value of the handle?

#### Answer:
null

#### Question:
If your popups are being blocked and the user is on Internet Explorer, what is the type of the handle? Don't put it in quotes.

#### Answer:
undefined

#### Question:
What 2-character operator do you need to use to test for popup blockers in all browsers?

#### Answer:
`||`

#### Question:
What value signals a popup blocker in browsers other than Internet Explorer?

#### Answer:
`null`

#### Question:
What value signals a popup blocker in Internet Explorer? Include the quotation marks.

#### Answer:
`"undefined"`

#### Question:
Fill in the blank.
`if (__________(testPop) === "undefined") {`

#### Answer:
`if (typeof(testPop) === "undefined") {`

#### Question:
Code the first line of an if statement that tests for a popup blocker on browsers other than the Internet Explorer.

#### Answer:
`if (test === null) {`
  
#### Question:
Display a paragraph with text content "Whee!" in a window that's already open, whose handle is pop.

#### Answer:
`pop.document.write("<p>Whee!</p>");`
