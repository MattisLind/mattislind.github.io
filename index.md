---
layout: default
title: Datormuseum projects
---

# Articles

<ul>
{%- for post in site.posts -%}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{%- endfor -%}
</ul>

## Other pages
- <a href="/VAXStationIIGPX.html">VAXStation II/GPX project</a>
