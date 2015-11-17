---
layout: page
title: 欢迎来到灵魂拾荒者的空间!
tagline: Supporting tagline
---
{% include JB/setup %}
<div>
欢迎扫描右上角二维码关注公众号"灵魂拾荒者"
<br>
<br>
<br>
<h3>日志列表</h3>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
