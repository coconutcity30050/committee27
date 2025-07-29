---
layout              : page
show_meta           : false
title               : "管委會之會議紀錄"
subheadline         : "恪守規約, 委員有責"
teaser              : "一切共識決議,依管理委員會決議執行規定事項"
header:
   image_fullwidth  : "header_unsplash_3.jpg"
permalink           : "/committee-meetings/"
---
## 會議紀錄
<br>
<h3>
<ul>
    {% for post in site.tags.meetings %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
</h3>

---
