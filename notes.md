---
title: Notes
permalink: /notes/
description: Notes, observations, and things worth sharing.
---

<section class="shell page-wrap">
  <header class="page-header compact-header"><p class="eyebrow">Notebook</p><h1>Ideas in<br><em>progress.</em></h1><p class="page-lead">Notes, observations, and things worth sharing.</p></header>
  <div class="notes-list">
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        <article class="note-row"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%b %-d, %Y" }}</time><div><h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>{% if post.excerpt %}<p>{{ post.excerpt | strip_html | truncatewords: 24 }}</p>{% endif %}</div><a class="note-arrow" href="{{ post.url | relative_url }}" aria-label="Read {{ post.title }}">→</a></article>
      {% endfor %}
    {% else %}
      <div class="empty-state"><p>No notes yet. The first one is taking shape.</p></div>
    {% endif %}
  </div>
</section>
