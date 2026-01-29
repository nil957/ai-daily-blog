---
layout: default
title: AI Daily Blog
---

## 📰 文章列表

{% for post in site.posts %}
<div style="background: #f6f8fa; border-radius: 8px; padding: 20px; margin-bottom: 16px;">
  <span style="color: #666; font-size: 14px;">{{ post.date | date: "%Y年%m月%d日" }}</span>
  <h3 style="margin: 8px 0;"><a href="{{ post.url | relative_url }}" style="color: #0366d6; text-decoration: none;">{{ post.title }}</a></h3>
  <p style="color: #586069; margin: 0;">{{ post.description | default: post.excerpt | strip_html | truncate: 150 }}</p>
</div>
{% endfor %}

---

*每日更新，追踪 AI 前沿动态* ✨
