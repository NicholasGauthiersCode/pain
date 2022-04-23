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

<a href="https://nickgauth.github.io/pain/">click here to go to home page test</a>

[calculus homepage][calchp]

[calchp]: https://nickgauth.github.io/pain/jekyll/update/2022/04/22/welcome-to-jekyll.html
