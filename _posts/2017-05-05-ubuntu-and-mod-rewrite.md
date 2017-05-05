---
layout: post
title: Ubuntu And mod_rewrite
---

{% highlight shell %}
  sudo a2enmod rewrite && sudo service apache2 restart
{% endhighlight %}

<p>AllowOverride is set to None, set it to All, assuming Apache2.4</p>

{% highlight shell %}
  sudo nano /etc/apache2/apache2.conf
{% endhighlight %}

<p>search for <strong><Directory /var/www/></strong> and change AllowOverride None to <strong>AllowOverride All</strong>, then save the file and restart apache</p>
