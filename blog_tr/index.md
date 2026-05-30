---
layout: base
title: Blog (Türkçe)
description: Science outreach and articles in Turkish by Ali Aydogdu.
---

## Türkçe Yazılar

<ul class="post-list">
{% for post in site.tags.turkce %}
    <li>
        <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
