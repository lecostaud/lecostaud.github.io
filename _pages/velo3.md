---
layout: single

Title: ¨les Vélos¨
permalink: /velob/
author_profile: true
veloavendre: 5
---


<h1>Les Vélos :</h1>

<ul>
  {% for page in site.pages %}
    {% if page.categories contains "velo" %}
        <li>
            <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
            <a href="{{ page.url }}"><img src="{{ page.image }}" width='400'></a>
            <br>
            {{ page.excerpt }}
        </li> 
    {% endif %}

    
  {% endfor %}
</ul>
nouvelle version :

<ul>
  {% for page in site.pages %}
    {% if page.categories contains "velo" %}
        <li>
            <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
            <figure class="half">
                <a href="{{ page.url }}"><img src="{{ page.image1 }}"></a>
                <a href="/assets/images/cargo02.jpg"><img src="/assets/images/cargo02.jpg"></a>
                <figcaption>{{ page.excerpt }}</figcaption>
            </figure>
            <br>
            
        </li> 
    {% endif %}

    
  {% endfor %}
</ul>

