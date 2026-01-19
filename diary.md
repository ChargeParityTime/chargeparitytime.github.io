---
layout: default
title: Diaries
permalink: /diary.html
---

# 📔 Diaries
A collection of my thoughts, research notes, and daily logs.

<ul>
  {% for post in site.posts %}
    <li>
      <span style="color:gray; font-size:0.8em;">{{ post.date | date: "%b %d, %Y" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---
[🔙 Back to Home](./)
