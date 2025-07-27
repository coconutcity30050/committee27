---
layout: page
subheadline: "Meeting Conclusions"
title: "會議決議"
teaser: "第27屆管委會會議決議"
header:
   image_fullwidth: "header_unsplash_3.jpg"
permalink: "/meeting-conclusion/"
---

<ul>
    {% for post in site.categories.meeting-conclusions %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
