---
layout: page
title: Témata
permalink: /temata/
---

{% assign sorted_tags = site.tags | sort %}

{% for tag in sorted_tags %}
## {{ tag[0] }}

<ul>
  {% assign posts = tag[1] | sort: "date" | reverse %}
  {% for post in posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
{% endfor %}
