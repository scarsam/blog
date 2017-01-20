---
layout: posts
title:  "Which ones could store the value of 500?"
tags: Java
---
This was an exercise to see which number could be stored in some of the different numeric types. In this case byte could only hold a maxium value of 128 which why it's the one that will fail.

{% highlight java %}
import javax.swing.*;

public class Fivehundred {
	public static void main (String[] arg) {
		int i = 500;
		byte b = 500;
		double d = 500;
	}
}
{% endhighlight %}
