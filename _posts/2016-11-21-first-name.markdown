---
layout: posts
title:  "First name uppercase dialog"
---
In this example I have the user input their full name like this (Lastname, Firstname). I then look up the character , and add +1 and substring it from the fullname to swap the order of the input.

{% highlight java %}
import javax.swing.*;

public class FirstNameDialog {
	public static void main (String[] arg) {
		String fullname =	JOptionPane.showInputDialog("Type your name Lastname, Firstname"); // Creating a message dialog with the stored varibles in fullname
		int lastname = fullname.lastIndexOf(',');
		String firstname = fullname.substring(lastname+1);
		JOptionPane.showMessageDialog(null, "Hello your name is: " + firstname.toUpperCase());
	}
}
{% endhighlight %}
