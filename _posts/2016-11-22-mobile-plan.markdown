---
layout: posts
title:  "Monthly cost for your mobile plan"
---
Placeholder

{% highlight java %}
import javax.swing.*;

public class MobilePlan {
	public static void main (String[] arg) {
    String a = JOptionPane.showInputDialog("How many minutes do you call per month?");
    int minutes = Integer.parseInt(a);
    a = JOptionPane.showInputDialog("Price per minute?");
    double price = Double.parseDouble(a);
    double result = a*price;
    JOptionPane.showMessageDialog(null, "Montlhy price: " + result);
	}
}
{% endhighlight %}
