---
layout: clean
title: "Blog"
permalink: /blog/
redirect_from:
  - /year-archive/
---

Notes and thoughts on reading, the brain, neuroimaging methods and research life.
<a href="{{ '/feed.xml' | relative_url }}" title="RSS feed"><i class="fa-solid fa-rss"></i> RSS</a>

{% if site.posts.size == 0 %}
<p class="meta">First posts coming soon.</p>
{% else %}
{% assign by_year = site.posts | group_by_exp: "p", "p.date | date: '%Y'" %}
{% for year in by_year %}
<h2>{{ year.name }}</h2>
<ul class="post-list">
  {% for post in year.items %}
  <li>
    <span class="post-date">{{ post.date | date: "%b %-d" }}</span>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    {% if post.excerpt %}<div class="post-excerpt">{{ post.excerpt | strip_html | truncatewords: 30 }}</div>{% endif %}
  </li>
  {% endfor %}
</ul>
{% endfor %}
{% endif %}
