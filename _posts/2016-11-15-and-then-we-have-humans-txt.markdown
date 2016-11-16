---
layout: post
comments: true
title:  "And then we have humans.txt"
date:   2016-11-15 14:15:16
categories: humans txt
---

`humans.txt` is a txt file that you add in the top-level directory of your web server and that contains information about all the people
involved in the construction of the website.

The following is a suggestion given by [humanstxt]:  http://humanstxt.org/Standard.html of the content that can go in the humans.txt file:

{% highlight ruby %}

/* TEAM */
Your title: Your name.
Site: email, link to a contact form, etc.
Twitter: your Twitter username.
Location: City, Country.
...

/* THANKS */
Name: name or url
...

/* SITE */
Last update: YYYY/MM/DD
Standards: HTML5, CSS3,..
Components: Modernizr, jQuery, etc.
Software: Software used for the development
{% endhighlight %}

The [humanstxt]: http://www.humanstxt.org website also recomends adding an author tag on the head of the site.

{% highlight ruby %}

<link type="text/plain" rel="author" href="http://domain/humans.txt" />

{% endhighlight %}


For this assignment I created an empty txt file in WebStorm and copied the basic structure given by humanstxt.org.
Later on I added all the real information necessary, modified a couple things and that was it. Very fast and simple.



