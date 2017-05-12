---
layout: post
title: Youtube-dl with Ubuntu
date: 2017-05-12 18:40:45 +02:00
---
<p>Install python</p>

{% highlight shell %}
  sudo apt-get install python
  sudo apt-get install python-setuptools
  sudo easy_install pip
{% endhighlight %}

<p>These last 2 commands are needed to be able to update the youtube-dl.</p>

<p>ANd now we can install youtube-dl with command</p>
{% highlight shell %}
  sudo apt-get install youtube-dl
{% endhighlight %}

<p>And we can check for the latest version by using this command</p>
{% highlight shell %}
  sudo pip install --upgrae youtube-dl
{% endhighlight %}

<hr>

<p>Extract audio from youtube video as <strong>mp3</strong></p>
{% highlight shell %}
  youtube-dl --extract-audio --audio-format mp3 http://....
{% endhighlight %}

<p>Download youtube <strong>playlist</strong></p>
{% highlight shell %}
  youtube-dl -cit http://
{% endhighlight %}
