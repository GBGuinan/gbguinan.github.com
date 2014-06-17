---
layout: page
title: George's blog
tagline: work in progress
---
{% include JB/setup %}




    
## Tuesday

This was an extremely long day in every way, while I'm not sure exactly what I learnt I feel strengthened somehow, confused, bloodied but unbowed.

    
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

work on workflow, structured collaboration, tomatina timer?



