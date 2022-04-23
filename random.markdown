---
layout: page
title: Notes
permalink: /notes/
---

Does this work


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<a href="{{index.markdown}}">click here to go to home page</a>
