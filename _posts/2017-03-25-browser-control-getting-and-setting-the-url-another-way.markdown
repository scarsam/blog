---
layout: posts
title:  "Browser control: Getting and setting the URL another way"
tags: Javascript
---

#### Question:
The current page is to be included in the browser history when the new page loads. Fill in the blank.
`window.location._______("http://www.wow.com");`

#### Answer:
`window.location.assign("http://www.wow.com");`

#### Question:
The current page is to be excluded from the browser history when the new page loads. Fill in the blank.
`window.location._______("http://www.wow.com");`

#### Answer:
`window.location.replace("http://www.wow.com");`

#### Question:
The statement refreshes the current webpage. Fill in the blank.
`window.location.________();`

#### Answer:
`window.location.reload();`

#### Question:
What word forces the browser to reload the page from the server?

#### Answer:
`true`

#### Question:
Code a statement that explicitly, using a Boolean, tells JavaScript to refresh the current page from the cache if the page is cached.

#### Answer:
`window.location.reload(false);`

#### Question:
Code a statement that directs the browser to a new URL (make up the name) and excludes the current page from the browser history.

#### Answer:
`window.location.replace("http://www.hello.com");`

#### Question:
Code a statement that tells JavaScript to refresh the current page from the cache if the page is cached, without using false.

#### Answer:
`window.location.reload();`

#### Question:
Using either approach you learned in this chapter, direct the browser to wikipedia.org.

#### Answer:
`window.location.assign("http://www.wikipedia.org");`

#### Question:
Using either of the approaches you learned in this chapter, direct the browser to the questions subdirectory of stackoverflow.com

#### Answer:
`window.location.assign("http://www.stackoverflow.com/questions");`
