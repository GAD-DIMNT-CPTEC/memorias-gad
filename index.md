---
layout: home
title: "Memórias das Reuniões do GAD"
---

{% assign posts = site.posts %}
{% if posts and posts.size > 0 %}
<ul>
{% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a><br>
    <small>{{ post.date | date: site.minima.date_format }}</small>
    {% if post.excerpt %}<p>{{ post.excerpt }}</p>{% endif %}
  </li>
{% endfor %}
</ul>
{% else %}
> Ainda não há atas publicadas.
{% endif %}

