---
layout: default
title: Home
---
# {{ site.title }}

{{ site.description }}

## Upcoming sessions

<ul>
{% assign future_sessions = site.sessions | sort: "date" %}
{% for s in future_sessions %}
  <li>
    <a href="{{ s.url }}">{{ s.title }}</a>
    — {{ s.date }} at {{ s.start_time }} ({{ s.location }})
  </li>
{% endfor %}
</ul>

<p><a href="/info/">Important info & files</a></p>