<meta name="google-site-verification" content="6-6HckY_4cCA1xYkYpqcXxwyzC82a0mIyZswI0MdSao" />

---
layout: default
title: 语料库存档
---

# 文章列表

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y年%m月%d日" }}
    </li>
  {% endfor %}
</ul>