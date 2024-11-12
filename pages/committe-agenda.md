---
layout              : page
show_meta           : false
title               : "管委會之會議議程"
subheadline         : "恪守規約, 委員有責"
teaser              : "一切共識決議,依管理委員會決議執行規定事項"
header:
   image_fullwidth  : "header_homepage_13.jpg"
permalink           : "/committe-agenda/"
---

## 會議須知

### 社區規約規定如下：

1. 每月召開至少一次會議

2. 依管理委員會決議執行規定事項

---
## 會議議程

### 2024/10/17 第27屆管理委員選舉
* 完成管理委員選舉 --> 已公告<br>

### 2024/10/29 8pm 第27屆管委會委員互選
* 完成委員互選 --> 已於11/1公告管理委員名單<br>

### 2024/11/12 7pm~9pm 11月第一次會議

<ul>
    {% for post in site.tags.agenda %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

---
