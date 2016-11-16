---
layout: post
comments: true
title:  "Static Site Generators"
date:   2016-11-14 20:20:20
categories: static site generators
---

Static site generators have been getting more and more popular. They are a very good option for creating sites that do not need
real time content or need to be updated by common users. Overall I think static site generators are quite useful. I have though,
seen very similar benefits when using PHP.

The first advantage of the generators are the `includes`. Separate files that contain different areas of the webpage. So if something
needs to be changed in the navigation, for example, you would just have to change it once and it will be seen on the entire website.
The second benefit is `layouts `. By using these, you get to manipulate and control the way different pages look through a centralized
system. And thirdly, you get a much easier `version control`. In this area the PHP approach would fall behind completly.
It is extremely handy to be able to manage different versions in a seamless way. Jekyll for example, which is the
static site generator used in this assignment works very well with GitHub.


As with any of the other new techniques used in this assignment, it takes a while to get used to it and to learn how everything is done.
Which is something to take into consideration when building a website. The only big issues I found
was the update of content in robots.txt and humans.txt and the update of image files that were already added to page(s). In all these
three cases
I had to manually delete the txt or image files in src in order for Jekyll to generate the correct public version.

In conclusion, I would say static site generators are good for projects that do not need to be updated often. The person in charged of updating it
 would also have to be
someone that is relatively comfortable with the necessary technical knowledge.
If the person responsible is a everyday user, I would probably suggest instead
a CMS, or if the website would be a site whose profit comes mainly from updated/real time content then a database approach it is probably the way to go.


