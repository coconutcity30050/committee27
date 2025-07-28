---
layout: page
show_meta: false
title: "場所與設備"
subheadline: "社區各場所與設備現況"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/places/"
---

## 社區門牌號碼對照圖

![](https://github.com/coconutcity30050/community/raw/gh-pages/images/coconutcity_address_map.jpg)

<ul>
    {% for post in site.categories.places %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
