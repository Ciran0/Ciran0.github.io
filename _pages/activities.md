---
title: "Activities"
permalink: /activities/
layout: single
---

Here is a summary of the various activities and learning experiences I've undertaken.

## All Activities

<ul>
  {% for activity in site.activities %}
    <li>
      <a href="{{ activity.url | relative_url }}">{{ activity.title }}</a>
    </li>
  {% endfor %}
</ul>
