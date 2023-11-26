---
layout: posts
read_time: true
categories: jekyll images
toc: true
toc_label: "My Table of Contents"
---

# Titre 1
## voici un test d'un article avec des **images**
explications ici :
[https://mmistakes.github.io/minimal-mistakes/markup-more-images/#one-up](https://mmistakes.github.io/minimal-mistakes/markup-more-images/#one-up)
### Image markdown (non cliquable) :
```
![image cargo](/assets/images/cargo01.jpg)
```
![image cargo](/assets/images/cargo01.jpg)

### lien vers une image :
```
[image](/assets/images/cargo01.jpg)
```
[image](/assets/images/cargo01.jpg)

### deux images cotes à cotes
<figure class="half">
    <a href="/assets/images/cargo01.jpg"><img src="/assets/images/cargo01.jpg"></a>
    <a href="/assets/images/cargo02.jpg"><img src="/assets/images/cargo02.jpg"></a>
    <figcaption>Premier prototype d'un vélo cargo</figcaption>

</figure>
  

### une image
<figure class="one">
    <a href="/assets/images/cargo01.jpg"><img src="/assets/images/cargo01.jpg"></a>
    <figcaption>Premier prototype d'un vélo cargo</figcaption>
</figure>
enlever le < a > pour que l'image ne soit pas cliquable