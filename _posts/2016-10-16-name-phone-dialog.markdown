---
layout: posts
title:  "Dialog x2"
---
This code is very similar to the first code I wrote, but this one will show two dialogs after each other instead.

{% highlight java %}
import javax.swing.*;

public class NamePhone {
	public static void main (String[] arg) {
		JOptionPane.showMessageDialog(null, "Sam");
		JOptionPane.showMessageDialog(null, "415.321.9307");	}
}
{% endhighlight %}