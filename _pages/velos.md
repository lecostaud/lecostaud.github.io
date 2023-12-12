---
layout: single

Title: ¨Vélos à vendre¨
permalink: /velos/
author_profile: true
veloavendre: 5
---
# Les vélos à vendre
<ul>
  {% for page in site.pages %}
    {% if page.categories contains "velo" %}
        <li>
            <h2><a href="{{ page.url }}"> {{ page.title }}</a> {{ page.etat }}</h2>
            {{ page.excerpt }}
            <figure class="one">
                <a href="{{ page.url }}"><img src="{{ page.image1 }}"></a>
                <figcaption></figcaption>
            </figure>
            
        </li> 
    {% endif %}
  {% endfor %}
</ul>


