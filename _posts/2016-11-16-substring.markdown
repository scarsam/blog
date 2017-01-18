---
layout: posts
title:  "Substring method"
---
Here I'm using `substring` to take out part of the string and put into another varible.

{% highlight java %}
import javax.swing.*;

public class substring {
	public static void main (String[] arg) {
		String a, b; 
		a = "Programming language";
		b = a.substring(3, 7); // Takes out the word  between charachter 4-7 = gram
		JOptionPane.showMessageDialog(null, b); // This will say gram
	}
}
{% endhighlight %}
