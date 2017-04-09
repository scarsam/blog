---
layout: posts
title:  "Lambda School Assignment 4"
tags: Javascript
---

### Homework URL:
`https://github.com/SunJieMing/js-minicamp-homework-4`

#### Question:
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
* Callback Functions
* Closure
* arguments array
* recursion
* prototype
* constructors

#### Answer:
* Callback Functions
  * Callback functions are function inside another function that will get triggered once you call them.
* Closure
  * ?
* arguments array
  * ?
* recursion
  * ?
* prototype
  * ?
* prototype
  * ?

#### Question:
* use the arguments keyword to multiply all of the arguments together and return the product
* if no arguments are passed in return 0
* if one argument is passed in just return it

#### Answer:
{% highlight javascript %}
function multiplyArguments() {
	if (arguments.length === 0) {
		return 0;
	}
	else {
		var total = 1;
		for (var i = 0; i < arguments.length; i++) {
			total *= arguments[i];
		}
	}
	return total;
}
{% endhighlight %}

#### Question:
* invoke cb

#### Answer:
{% highlight javascript %}
function invokeCallback(cb) {
	cb();
}
{% endhighlight %}

#### Question:
* sum up all of the integers in the numbers array
* pass the result to cb
* no return is necessary

#### Answer:
{% highlight javascript %}
function sumArray(numbers, cb) {
	var total = 0;
	numbers.forEach(function(num) {
		total += num;
	});
	cb(total);
}
{% endhighlight %}

#### Question:
* iterate over arr and pass its values to cb one by one
* hint: you will be invoking cb multiple times (once for each value in the array)

#### Answer:
{% highlight javascript %}
function forEach(arr, cb) {
	arr.forEach(function(num) {
		cb(num);
	});
}
{% endhighlight %}

#### Question:
* create a new array
* iterate over each value in arr, pass it to cb, then place the value returned from cb into the new arr
* the new array should be the same length as the array argument

#### Answer:
{% highlight javascript %}
function map(arr, cb) {
	var newArr = arr.map(function(value) {
		return cb(value);
	});
	return newArr;
}
{% endhighlight %}

#### Question:
* create a constructor called User
* it should accept an options object with username, name, email, and password properties
* in the constructor set the username, name, email, and password properties
* the constructor should have a method 'sayHi' on its prototype that returns the string 'Hello, my name is {{name}}'
* {{name}} should be the name set on each instance
* return the constructor

#### Answer:
{% highlight javascript %}
function getUserConstructor() {
	function User(options) {
		this.username = options.username;
		this.name = options.name;
		this.email = options.email;
		this.password = options.password;
	}
	User.prototype.sayHi = function() {
		return 'Hello, my name is ' + this.name;
	};
	return User;
}
{% endhighlight %}

#### Question:
* add a method to the constructor's prototype
* the method should be called 'sayHi' and should return the string 'Hello World!'

#### Answer:
{% highlight javascript %}
function addPrototypeMethod(Constructor) {
	Constructor.prototype.sayHi = function() {
			return 'Hello World!';
	};
}
{% endhighlight %}

#### Question:
* add a method to the string constructor's prototype that returns a reversed copy of the string
* name this method reverse
* hint:
* you will need to use 'this' inside of reverse

#### Answer:
{% highlight javascript %}
function addReverseString() {
	String.prototype.reverse = function() {
		var newStr = '';
		for (var i = this.length - 1; i>=0; i--) {
			newStr += this[i];
		}
		return newStr;
	};
}
{% endhighlight %}

#### Question:
* return the factorial for n
* solve this recursively
* example:
* the factorial of 3 is 6 (3 * 2 * 1)

#### Answer:
{% highlight javascript %}
function nFactorial(n) {
	if (n === 0) {
		return 1;
	}
	return n * nFactorial(n - 1);
}
{% endhighlight %}
