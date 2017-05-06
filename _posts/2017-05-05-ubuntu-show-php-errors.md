---
layout: post
title: Ubuntu Show PHP Errors
date: 2017-05-05 22:43:22 +02:00
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
