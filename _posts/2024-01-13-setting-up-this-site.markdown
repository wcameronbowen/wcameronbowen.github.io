---
layout: post
title:  "How I Setup This Site"
date:   2024-01-13 14:00:00 -0600
categories: jekyll
---
Setting up ruby on fedora laptop.

1. install ruby from dnf
{% highlight bash %}
sudo dnf install ruby ruby-devel openssl-devel redhat-rpm-config gcc-c++ @development-tools
{% endhighlight %}

2. install jekyll
{% highlight bash %}
gem install jekyll bundler
{% endhighlight %}
