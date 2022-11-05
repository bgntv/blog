
### My Posts

{% for post in site.posts %}
  <article>
    <h2>
        <a href="{{ site.url }}{{ post.url }}">
            {{ post.title }}
        </a>
    </h2>
  </article>
{% endfor %}
---
layout: home
list_title: The latest from bgn.tv
title: ''
theme: minima
---