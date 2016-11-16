---
layout: post
comments: true
title:  "What about robots.txt?"
date:   2016-11-14 20:30:16
categories: robots txt
---

`robots.txt` is a file that you add in the top-level directory of your web server and whose purpose is to suggest a certain behaviour to visiting web robots.
It is not mandatory for them to follow the guidelines, though. Something very important to have in mind. You cannot really hide information
using this file.

The content in the robots.txt file is very simple.

{% highlight ruby %}
User-agent: *
Disallow: /cgi-bin/
{% endhighlight %}

The `user-agent` part specifies which robots the file applies to, in the example above it means all.
The `disallow` part refers to pages or directories that should not be visited by the robot. In the example above it applies to cgi.bin.

For this assignment I created a empty txt file in WebStorm and wrote the basic lines needed. Then I added some extra disallow lines for directories
I don't really want to be indexed or visited by robots.
