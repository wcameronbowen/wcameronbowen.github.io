---
layout: post
title:  "How I Setup This Site"
date:   2024-01-13 13:40:00 -0600
categories: jekyll
---

### Setup Ruby and Jekyll (on Fedora)
You would think that parenthetical doesn't make a difference, more on that to come.

1. install ruby from dnf
{% highlight bash %}
sudo dnf install ruby ruby-devel openssl-devel redhat-rpm-config gcc-c++ @development-tools
{% endhighlight %}

2. install jekyll
{% highlight bash %}
gem install jekyll bundler
{% endhighlight %}

3. also had to install webrick to get `jekyll serve` to work
{% highlight bash %}
bundle add webrick
{% endhighlight %}
