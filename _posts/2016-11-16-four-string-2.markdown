---
layout: posts
title:  "Another way of declaring varibles"
---
In this case I declare each variable on a new row and assign it a value for example: `String name = "Sam"`;. With this method It's a lot more clear what kind of varible type each varible is.

{% highlight java %}
import javax.swing.*;

public class FourString2 {
	public static void main (String[] arg) {
		String name = "Sam";
		String address = "1325 Mason st";
		String phone = "415.321.9307";
		String info = name + "\n" + address + "\n" + phone;
		JOptionPane.showMessageDialog(null, info);
	}
}
{% endhighlight %}
