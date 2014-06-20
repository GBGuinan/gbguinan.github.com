
---
layout: page
title: George's blog
tagline: work in progress
---
{% include JB/setup %}




    
## Tuesday

git@github.com:GBGuinan/gbguinan.github.com.git

    
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

work on workflow, , tomatina timer?



