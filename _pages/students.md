---
title: "UMD GRAD-MAP - Students"
layout: gridlay
excerpt: "UMD GRAD-MAP - Students"
sitemap: false
permalink: /students
---
<center>
  <img src="{{ site.url }}{{ site.baseurl }}/images/1.png" width="100%" />
</center>

{% assign number_printed = 0 %}
{% for member in site.data.ss_current %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive"  width="150px" height="240px" style="float: left" />
  <h4>{{ member.name }}</h4>
  Mentor: <i>{{ member.adviser }}</i> <br> {{ member.info }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<br>

