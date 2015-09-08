---
layout: page
title: 
tagline: Supporting tagline
---
{% include JB/setup %}
    
### Welcome!

Thanks for visiting the page for our podcast. 

### Upcoming Episode

For our inaugural podcast, we'll be introducing ourselves and setting up our forthcoming podcast on the papal visit to the United States.  Get to know our team and how we got interested in theology.

### Previous Episodes

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


