---
layout: posts
title:  "Counting words and order of the words"
---
In this example I'm counting all the characters and also display which word that gets displayed first and last in the order.

{% highlight java %}
import javax.swing.*;

public class CountOrder {
	public static void main (String[] arg) {
		String message =	JOptionPane.showInputDialog("Enter a message with at least two words"); // Creating a message dialog with the stored varibles in fullname
		int messageLength = message.length();
		message = message.trim();	
		int firstWord = message.indexOf(' ');
		int lastWOrd = message.lastIndexOf(' ');
		JOptionPane.showMessageDialog(null, 
				"Your text is: " + messageLength + " characters" +
				"\nFirst word you wrote was \"" + message.substring(0, firstWord) + '"' +
				"\nLast word you wrote was \"" + message.substring(lastWOrd+1) + '"');
	}
}
{% endhighlight %}
