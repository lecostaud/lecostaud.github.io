---
layout: single

Title: ¨les Vélos¨
permalink: /velos/
author_profile: true
veloavendre: 5
---
# Les vélos
<ul>
  {% for page in site.pages %}
    {% if page.categories contains "velo" %}
        <li>
            <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
            <figure class="half">
                <a href="{{ page.url }}"><img src="{{ page.image1 }}"></a>
                <a href="{{ page.url }}"><img src="{{ page.image2 }}"></a>
                <figcaption>{{ page.excerpt }}</figcaption>
            </figure>
            <br>
            
        </li> 
    {% endif %}

    
  {% endfor %}
</ul>

