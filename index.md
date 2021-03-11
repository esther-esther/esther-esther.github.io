---
layout: default
---
# More than Anything
 Some Musings

<ul>
  {% for post in site.posts %}
  <br>
      <a href="{{ post.url }}">{{ post.title }}</a>
  <br>
  {% endfor %}
</ul>
