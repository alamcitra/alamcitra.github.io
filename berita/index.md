---
layout: page
title: Berita Warga
excerpt: "Berita dan dokumentasi kegiatan Warga Perumahan Alam Citra"
search_omit: true
image:
  feature: gerbang-alam-citra-malam.jpg
---

<ul class="post-list">
{% for post in site.categories.berita %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
