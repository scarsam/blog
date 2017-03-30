---
layout: posts
title:  "Form validation: email"
tags: Javascript
---

#### Question:
This is the first line of an if statement that tests whether a space occurs in the string represented by `eEntered`. Fill in the blank.
`if (eEntered.indexOf(___) !== -1) {`

#### Answer:
`if (eEntered.indexOf(" ") !== -1) {`

#### Question:
This is the first line of an if statement that tests whether a space occurs in the string represented by `eEntered`. Fill in the blank.
`if (eEntered._______(" ") !== -1) {`

#### Answer:
`if (eEntered.indexOf(" ") !== -1) {`

#### Question:
This is the first line of an if statement that tests whether a space occurs in the string represented by `eEntered`. Fill in the blank.
`if (__________indexOf(" ") !== -1) {`

#### Answer:
`if (eEntered.indexOf(" ") !== -1) {`

#### Question:
If a character doesn't occur in a string, what is its index?

#### Answer:
`-1`

#### Question:
Code the first line of an if statement that tests for a space in a string that has been assigned to a variable.

#### Answer:
`if (eEntered.indexOf(" ") !== -1) {`

#### Question:
Using a single test that checks for either possibility, code the first line of an if statement that tests whether "@" doesn't occur in a string represented by a variable, and also whether it's the first character in the string, either of which would signal an illegal email address.

#### Answer:
`if (valueEntered.indexOf("@") < 1) {`
If the index is -1, "@" is nowhere to be found. If the index is 0, "@" is the first character in the string.

#### Question:
Code the first line of an if statement that tests whether there are at least 2 characters after the dot in a string represented by a variable. Use the length of the variable to measure.

#### Answer:
`if (addr.indexOf(".") < addr.length - 2) {`

#### Question:
Code the first line of an if statement that tests whether there is not at least one character separating the "@" and the dot in the string represented by a variable.

#### Answer:
`if (val.indexOf(".") - val.indexOf("@") < 2) {`

#### Question:
This if statement tests whether there is not an "@" with a minimum of 1 character preceding it or whether there are not a minimum number of characters after it. Fill in the blank. Use the length of the variable to measure. Use `>`.
`if (addr.indexOf("@") > 0 || __________________ {`

#### Answer:
`if (addr.indexOf("@") > 0 || addr.indexOf("@") > addr.length - 5) {`
