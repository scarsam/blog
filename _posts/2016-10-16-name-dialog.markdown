---
layout: default
title:  "First code in Java"
---
This code will create a dialog saying "Hello". `JOptionPane.showMessageDialog();` is available through the `Java swing` library. Important to note is that `public class Hello` is the same as the filename of your Java file.

{% highlight java %}
import javax.swing.*;

public class Hello {
	public static void main (String[] arg) {
		JOptionPane.showMessageDialog(null, "Hello");
	}
}
{% endhighlight %}
