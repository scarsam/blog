---
layout: posts
title:  "Browser control: Forward and reverse"
tags: Javascript
---

#### Question:
What word is used in all statements that move the browser backward and forward?

#### Answer:
`history`

#### Question:
In addition to `history`, a dot, and a semicolon at the end, there are 2 characters that are always part of a statement that moves the browser backward and forward. Type the characters in the order in which they appear.

#### Answer:
`()`

#### Question:
What keypress has the same effect as history.back()? Answer with lower-case characters.

#### Answer:
backspace

#### Question:
The browser is on page1.html. There is no history. The statement history.go(-1)executes. What page does the browser land on?

#### Answer:
page1.html

#### Question:
Direct the browser to back up 1 URL without using the word go.

#### Answer:
`history.back();`

#### Question:
Direct the browser to skip ahead 1 URL without using the word go.

#### Answer:
`history.forward();`

#### Question:
What is the alternative way to code history.back()?

#### Answer:
`history.go(-1);`

#### Question:
The user clicked a link to reach the current page. Assign the URL that contained the link to a variable, which hasn't been declared beforehand.

#### Answer:
`var whereItCameFrom = document.referrer;`
