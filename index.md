---
title: billder
description: Bill DeRouchey
layout: default
---

{: .large}
Oh hello there. Various thoughts via my typey-type machine...

<hr>

{% for post in site.posts %}
  <div class="blog-item">
    <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
    <p class="meta">{{ post.date | date_to_string }}</p>
    <p class="meta"><i>{{ post.description }}</i></p>
  </div>
{% endfor %}




