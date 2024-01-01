---
layout: single
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
    
        <li>
            <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
            <a href="{{ post.url }}"><img src="{{ post.header.teaser}}" width="200"></a><br>
            {{ post.excerpt }}<br>
        </li> 

  {% endfor %}
</ul>