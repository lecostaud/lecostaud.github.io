---
layout: single

Title: ¨les Vélos¨
permalink: /veloa/
author_profile: true
veloavendre: 5
---

Il y a actuellement {{ page.veloavendre }} vélos à vendre



<h1>Les Vélos :</h1>

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "velo" %}
        <li>
            <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
            {{ post.excerpt }}
        </li> 
    {% endif %}

    
  {% endfor %}
</ul>

