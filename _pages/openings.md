---
title: "UMD GRAD-MAP - Students"
layout: textlay
excerpt: "Openings"
sitemap: false
permalink: /vacancies
---
# 2024 Summer Scholars Cohort
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/DSC_0696.jpg" width="95%">
</figure>
# Program Alumni
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>
