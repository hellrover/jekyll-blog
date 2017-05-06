---
layout: post
title:  Jekyll Live Reload
date:   2017-05-04 12:30:11 +02:00
---

<blockquote>
  Hawkins is a Jekyll 3.1+ plugin that incorporates LiveReload into the Jekyll “serve” process.
</blockquote>

<p>Add the following to the <strong>Gemfile</strong> in the root of the project:</p>

{% highlight ruby %}
  group :jekyll_plugins do
    gem 'hawkins'
  end
{% endhighlight %}

<p>
  Then run <strong>bundle install.</strong>
</p>
<p>Start the server with: </p>

{% highlight ruby %}
  jekyll liveserve
{% endhighlight %}
