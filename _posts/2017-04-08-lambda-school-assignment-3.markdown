---
layout: posts
title:  "Lambda School Assignment 3"
tags: Javascript
---

### Homework URL:
`https://github.com/SunJieMing/js-minicamp-homework-3`

#### Question:
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
* Objects
* Properties
* Methodss
* for in loop
* dot notation vs bracket notation

#### Answer:
* Objects
  * Objects are variables that can contain many different values.
* Properties
  * Properties are name and value pairs inside the objects.
* Methods
  * Are actions that are stores inside objects. Functions are called methods when they're inside an Object.
* for in loop
  * Are looping through all the properties inside an Object
* dot notation vs bracket notation
  * The difference is that you can use variable names in bracket notation, it's also useful if you want to loop through your properties. Dot notation is faster to write and clearer to read. Square bracket notation allows access to properties containing special characters and selection of properties using variables

#### Question:
* Create a new object with a name property with the value set to the name argument
* add an age property to the object with the value set to the age argument
* add a method called meow that returns the string 'Meow!'
* return the object

#### Answer:
{% highlight javascript %}
function makeCat(name, age) {
  var cat = {
    name: name,
    age: age,
    meow: function() {
      return 'Meow!';
    }
  };
  return cat;
}
{% endhighlight %}

#### Question:
* add the property to the object with a value of null
* return the object
* note: the property name is NOT 'property'.  The name is the value of the argument called property (a string)

#### Answer:
{% highlight javascript %}
function addProperty(object, property) {
  object[property] = null;
  return object;
}
{% endhighlight %}

#### Question:
* method is a string that contains the name of a method on the object
* invoke this method
* nothing needs to be returned

#### Answer:
{% highlight javascript %}
function invokeMethod(object, method) {
  object[method]();
}
{% endhighlight %}

#### Question:
* mysteryNumberObject has a property called mysteryNumber
* multiply the mysteryNumber property by 5 and return the product

#### Answer:
{% highlight javascript %}
function multiplyMysteryNumberByFive(mysteryNumberObject) {
  var sum = mysteryNumberObject.mysteryNumber * 5;
  return sum;
}
{% endhighlight %}

#### Question:
* remove the property from the object
* return the object

#### Answer:
{% highlight javascript %}
function deleteProperty(object, property) {
  delete object[property];
  return object;
}
{% endhighlight %}

#### Question:
* create a new object with properties matching the arguments passed in.
* return the new object

#### Answer:
{% highlight javascript %}
function newUser(name, email, password) {
  var x = {
    name: name,
    email: email,
    password: password
  };
  return x;
}
{% endhighlight %}

#### Question:
* return true if the user has a value for the property 'email'
* otherwise return false

#### Answer:
{% highlight javascript %}
function hasEmail(user) {
  if (user.email) {
    return true;
  }
  return false;
}
{% endhighlight %}

#### Question:
* return true if the object has the value of the property argument
* property is a string
* otherwise return false

#### Answer:
{% highlight javascript %}
function hasProperty(object, property) {
  if (object.hasOwnProperty([property])) {
    return true;
  }
  else {
    return false;
  }
}
{% endhighlight %}

#### Question:
* check to see if the provided password matches the password property on the user object
* return true if they match
* otherwise return false

#### Answer:
{% highlight javascript %}
function verifyPassword(user, password) {
  if (password === user.password) {
    return true;
  }
  else {
    return false;
  }
}
{% endhighlight %}

#### Question:
* replace the existing password on the user object with the value of newPassword
* return the object

#### Answer:
{% highlight javascript %}
function updatePassword(user, newPassword) {
  user.password = newPassword;
  return user;
}
{% endhighlight %}

#### Question:
* user has a property called friends that is an array
* add newFriend to the end of the friends array
* return the user object

#### Answer:
{% highlight javascript %}
function addFriend(user, newFriend) {
  user.friends.push(newFriend);
  return user;
}
{% endhighlight %}

#### Question:
* users is an array of user objects.
* each user object has the property 'isPremium'
* set each user's isPremium property to true
* return the users array

#### Answer:
{% highlight javascript %}
function setUsersToPremium(users) {
  for (var i = 0; i < users.length; i++) {
    users[i].isPremium = true;
  }
  return users;
}
{% endhighlight %}

#### Question:
* user has an array property called 'posts'
* posts is an array of post objects
* each post object has an integer property called 'likes'
* sum together the likes from all the post objects
* return the sum

#### Answer:
{% highlight javascript %}
function sumUserPostLikes(user) {
  var sum = 0;
  for (var i = 0; i < user.posts.length; i++) {
    sum += user.posts[i].likes;
  }
  return sum;
}
{% endhighlight %}

#### Question:
* add a method to the storeItem object called 'calculateDiscountPrice'
* this method should multiply the storeItem's 'price' and 'discountPercentage' to get the discount
* the method then subtracts the discount from the price and returns the discounted price
* example:
* price -> 20
* discountPercentage -> .2
* discountPrice = 20 - (20 * .2)

#### Answer:
{% highlight javascript %}
function addCalculateDiscountPriceMethod(storeItem) {
  storeItem.calculateDiscountPrice =  function(){
    return (this.price - (this.price * this.discountPercentage));
  };
  return storeItem;
}
{% endhighlight %}
