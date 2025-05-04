---
title: "UMD GRAD-MAP - Gallery"
layout: gridlay
excerpt: "UMD GRAD-MAP -- Gallery"
permalink: /gallery
---

<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/4.png" width="100%" style="box-shadow: none; border: none; margin: 0 auto; display: block; width: 100%;" /> 
</center>
<br>

<div class="gallery">
  {% assign images = "1.png,2.png.3.png,4.png" | split: "," %}
  {% for img in images %}
    <figure>
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gallery/{{ img }}" alt="{{ img }}">
      <figcaption>{{ img | remove: ".jpg" | replace: "-", " " | capitalize }}</figcaption>
    </figure>
  {% endfor %}
</div>
