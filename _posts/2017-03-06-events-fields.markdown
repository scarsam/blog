---
layout: posts
title:  "Events: fields"
tags: Javascript
---

#### Question:
What is the keyword for detecting that the user has clicked in a field?

#### Answer:
`onFocus`

#### Question:
What is the keyword for detecting that a field no longer has the focus?

#### Answer:
`onBlur`

#### Question:
When the user clicks in the field, the function is called. Fill in the blank.
`<input type="text"__________"doSomething();">`

#### Answer:
`onFocus=`

#### Question:
When the text field loses the focus, the function gone executes. Fill in the blank.
`<input type="text" ___________________________`

#### Answer:
`onBlur="gone();">`

#### Question:
Code a text field. When the user clicks in it, call a function.

#### Answer:
`<input type="text" onFocus="hello();">`

#### Question:
Code a text field. When it loses the focus, call a function.

#### Answer:
`<input type="text" onBlur="hello();">`

#### Question:
Code a text field. When the user clicks in it, the field turns yellow.

#### Answer:
`<input type="text" onFocus="this.style.backgroundColor = 'yellow';">`

#### Question:
Code a text field. When it loses the focus, the field turns white.

#### Answer:
`<input type="text" onBlur="this.style.backgroundColor = 'white';">`

#### Question:
Code a text field. When the user clicks in it, a function executes. When the field loses focus, a different function executes.

#### Answer:
<input type="text" onFocus="hello();" onBlur="goodBye();">

#### Question:
Live coding exercise:
1) Code a text field that changes color when it receives the focus.

#### Answer:
{% highlight javascript %}

<input type="text" onFocus="this.style.backgroundColor = 'grey';">

{% endhighlight %}

#### Question:
Live coding exercise:
1) Code a text field that changes color when it receives the focus and reverts to white when it loses the focus.

#### Answer:
{% highlight javascript %}

<input type="text" onFocus="this.style.backgroundColor = 'grey';" onBlur="this.style.backgroundColor = 'white';">

{% endhighlight %}
