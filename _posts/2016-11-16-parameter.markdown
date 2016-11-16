---
layout: default
title:  "Parameter values"
---
By running `JOptionPane.showMessageDialog(null, [1], [2], [3]);` By changing one of these 3 parameters (null being default) you will get different results.
1. Needs to be included, text here will show up in the middle of the dialog.
2. Text here will show up in the top part of the dialog box.
3. This will display the icon to use for the dialog.


{% highlight java %}
import javax.swing.*;

public class DialogBox {
	public static void main (String[] arg) {
		JOptionPane.showMessageDialog(null, "Information Dialog", "Dialog 1", JOptionPane.INFORMATION_MESSAGE);
		JOptionPane.showMessageDialog(null, "Warning Dialog", "Dialog 2", JOptionPane.WARNING_MESSAGE);
		JOptionPane.showMessageDialog(null, "Error Dialog", "Dialog 3", JOptionPane.ERROR_MESSAGE);
	}
}
{% endhighlight %}
