**Notice:** This is an important info notice.
{: .notice}



<h1>Les Vélos :</h1>

<ul>
  {% for page in site.pages %}
    {% if page.categories contains "velo" %}
        <li>
            <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
            {{ page.excerpt }}
        </li> 
    {% endif %}

    
  {% endfor %}
</ul>


# Splash page :
---
layout: splash
feature_row:
  - image_path: /assets/images/cargo01.jpg
    alt: "vélo cargo 1"
    title: "Vélo cargo 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---
{% include feature_row %}


            <p class="notice">{{ page.etat }}</p>
            {{ page.excerpt }}<br>
            <figure class="one">