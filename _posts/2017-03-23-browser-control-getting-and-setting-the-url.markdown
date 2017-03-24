---
layout: posts
title:  "Browser control: Getting and setting the URL"
tags: Javascript
---

#### Question:
`http://www.a.com/pages/b.html#2`
Look at the URL shown above and tell me the value of `currentlyViewing`. It's a string, so enclose it in quotes.
`var currentlyViewing = window.location.href;`

#### Answer:
`"http://www.a.com/pages/b.html#2"`

#### Question:
`http://www.a.com/pages/b.html#2`
Look at the URL shown above and tell me the value of `currentSite`. It's a string, so enclose it in quotes.
`var currentSite = window.location.hostname;`

#### Answer:
`"www.a.com"`

#### Question:
`http://www.a.com/pages/b.html#2`
Look at the URL shown above and tell me the value of `currentPage`. It's a string, so enclose it in quotes.
`var currentPage = window.location.pathname;`

#### Answer:
`/pages/b.html"`

#### Question:
Look at the URL shown above and tell me the value of `pageSection`. It's a string, so enclose it in quotes.
`var pageSection = window.location.hash;`

#### Answer:
`"#2"`

#### Question:
Code a statement that detects the current URL and assigns it to a variable that hasn't been declared yet.

#### Answer:
`var x = window.location.href;`

#### Question:
Code a statement that detects the current site and assigns it to a variable that hasn't been declared yet.

#### Answer:
`var x = window.location.hostname;`

#### Question:
Code the first line of an if statement that tests whether the home page with no html file specified is currently loaded in the browser.

#### Answer:
`if (window.location.pathname === "/") {`

#### Question:
Have the browser navigate to the URL for uk.com

#### Answer:
`window.location.href = "http://www.uk.com";`

#### Question:
The string "http://www.uk.com/articles/number2033.html" has been assigned to the variable address. Add the anchor "#paragraph17" to the variable. Then use the variable to move the browser to the anchor.

#### Answer:
{% highlight javascript %}
address += "#paragraph17";
window.location.href = address;
{% endhighlight %}

#### Question:
1) Display the current URL in an alert.

#### Answer:
`alert(window.location.href);`

#### Question:
1) Display the current path in an alert.

#### Answer:
`alert(window.location.pathname);`
