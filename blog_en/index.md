---
layout: base
title: Blog
description: Science outreach and professional updates in English by Ali Aydogdu.
---

## Posts in English

<ul class="post-list">
{% for post in site.tags.english %}
    <li>
        <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
