---
layout: page
title: ぬけラボ
---
{% include JB/setup %}

hatenaはこちら -> [ぬけラボ](http://d.hatena.ne.jp/hiro_su/)

##最近の投稿

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

