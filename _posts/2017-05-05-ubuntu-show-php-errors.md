---
layout: post
title: Ubuntu Show PHP Errors
---
<p>Set <strong>display_errors = On</strong> in both php.ini files:</p>

<blockquote>
  <div>/etc/php5/apache2/php.ini</div>
  <div>/etc/php5/cli/php.ini</div>
</blockquote>

<p>Then restarting Apache:</p>

{% highlight shell %}
  sudo /etc/init.d/apache2 restart
{% endhighlight %}
