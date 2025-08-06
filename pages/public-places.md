---
layout: page
show_meta: false
title: "公共場所"
subheadline: "維護環境整潔，人人有責"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/public-places/"
---

## 社區門牌號碼對照圖

![](https://github.com/coconutcity30050/community/raw/gh-pages/images/coconutcity_address_map.jpg)

<ul>
    {% for post in site.categories.places %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
