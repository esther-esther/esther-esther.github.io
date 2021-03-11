---
layout: default
---

[My Thoughts](thoughts.md)   
[Things You Could Be Doing](boredthings.md)  
[For When You Forget Markdown...](https://www.markdownguide.org/cheat-sheet/)

# Alyson's site 
* sample list one 
* here is the secon item
* 


Here are all my blog posts in chronological order.....

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
