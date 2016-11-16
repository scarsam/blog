---
layout: default
title:  "Declare same variable type"
---
Here I have 4 string varibles with different names. Instead of saying that each of them is a string on each row I delcare them all the same varible type in this case `string` at the same time with: `String name, address, phone, info;`.

{% highlight java %}
import javax.swing.*;

public class FourString {
	public static void main (String[] arg) {
		String name, address, phone, info;
		name = "Sam";
		address = "1325 Mason st";
		phone = "415.321.9307";
		info = name + "\n" + address + "\n" + phone;
		JOptionPane.showMessageDialog(null, info);
	}
}
{% endhighlight %}
