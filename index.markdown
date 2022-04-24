---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
list_title: ' '
layout: home
---

<h2>Welcome to my website!</h2>

Here is a place that I will be able to put some of the intersting things that I am doing and... for more information about myself and this website checkout my <a href='https://nickgauth.github.io/pain/about/'>About Me</a> page! if you want to checkout what I am learning in school as an engineer, check out my <a href='https://nickgauth.github.io/pain/notes/'>Notes</a> or even my <a href='https://nickgauth.github.io/pain/projects'>Projects</a>!

<div class="posts">
  {% for post in paginator.posts %}
  {% if post.visible== 1  %}

  <div class="post">
    <h1>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>
        <a class="subtitle" href="{{ post.url }}">
           {{ post.excerpt }}
        </a>
      </a>
  </div>
  {% endif %}
  {% endfor %}
</div>
