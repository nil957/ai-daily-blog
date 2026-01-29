---
layout: default
---

## 📰 最新文章

{% for post in site.posts %}
<div class="post-card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncate: 120 }}</p>
</div>
{% endfor %}

---

*每日更新，追踪 AI 前沿动态* ✨
