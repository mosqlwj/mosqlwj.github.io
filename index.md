---
layout: home
title: 山水文墨
---

# 山水之间，学术之境

<p style="font-style: italic; text-align: center; font-size: 1.2rem;">
  书山有路勤为径，学海无涯苦作舟
</p>

## 最新文章

{% for post in site.posts limit:3 %}
<div class="post-card">
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p class="post-meta">{{ post.date | date: "%Y年%m月%d日" }}</p>
  <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
  <a href="{{ post.url }}" class="btn">阅读全文</a>
</div>
{% endfor %}

## 学术分类

- 论文笔记
- 研究进展
- 学术会议
- 读书心得

## 关于博主

一介书生，潜心学术，亦好山水诗文。
此博客记录学术探索之路，兼分享生活中的点滴感悟。
