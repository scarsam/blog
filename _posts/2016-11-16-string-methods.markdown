---
layout: posts
title:  "Substring and other methods"
---
Here I'm using `trim()` to remove unecessary spaces before and after my string, `lastIndexOf` to find the first of whatever is declared inside () in this case (' ') a space and `indexOf` that will find the first character that I'm asking for, in this case ('-'). After that I'm using substring to remove the part of the numbers I want by using `int` variable and then putting them together with the operators in this case `+`.

{% highlight java %}
import javax.swing.*;

public class substring2 {
	public static void main (String[] arg) {
		String a, b; 
		a = " Erik Anderssson 860314-2714 ";
		a = a.trim(); // removes the space in the beginning and at the end of the ""
		int i = a.lastIndexOf(' ') + 1; // finds the first empty space + 1 and puts them into a int variable that holds numbers
		int j = a.indexOf('-'); // finds the - character 
		b = a.substring(i, j); // takes out the numbers between int variable i and j
		b = b.substring(2, 4) + "/" + b.substring(4, 6); // took out 03 first and added a / with the operator to combined it with 14
		JOptionPane.showMessageDialog(null, b); // This will say 03/14
	}
}
{% endhighlight %}
