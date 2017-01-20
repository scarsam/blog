---
layout: posts
title:  "Dialog and Sound"
tags: Java
---
This code was created in the same way as my first `Java` code, but this example is also including a second `Java` library called `awt`. With this library we could use `Toolkit.getDefaultToolkit().beep();` which will tell the computer to make a sound after the first dialog have been executed.
{% highlight java %}
public class HelloBeep {
	public static void main (String[] arg) {
		JOptionPane.showMessageDialog(null, "Hello");
		Toolkit.getDefaultToolkit().beep();
	}
}
{% endhighlight %}