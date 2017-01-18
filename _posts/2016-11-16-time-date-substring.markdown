---
layout: posts
title:  "Time and date substring"
---
Here I wanted to just get the time from `Calendar.getInstance().getTime().toString();`. I used `.indexOf(':');` to find the : that the time was using and then did a substring -2 and +6 to move out just the time from the `Calendar.getInstance().getTime().toString();`

{% highlight java %}
import javax.swing.*;
import java.util.*;

public class TimeDateSubstring {
	public static void main (String[] arg) {
		String time = Calendar.getInstance().getTime().toString();
		int a = time.indexOf(':');
		JOptionPane.showMessageDialog(null, "The time is: " + time.substring(a-2, a+6));
	}
}

{% endhighlight %}
