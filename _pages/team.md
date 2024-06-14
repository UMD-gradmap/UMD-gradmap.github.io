---
title: "UMD GRAD-MAP - Team"
layout: gridlay
excerpt: "GRAD-MAP at the University of Maryland"
sitemap: false
permalink: /team/
---

# Meet our Team

<img src="{{ site.url }}{{ site.baseurl }}/images/gradmap_founders.png" class="img-responsive" title="GRAD-MAP founders: Dr. Ashlee Wilkins (left), Dr. Katie Jameson (center), and Dr. Alex McCormick (right)." width="40%" style="float: left" /> 
<br>
<span style="font-size:2em;"> We are a *graduate-student* powered initiative. </span>

GRAD-MAP is led by a team of graduate students from the Astronomy and Physics Departments at the University of Maryland, with support from faculty and staff in both departments, as well as many volunteers (students, researchers, and faculty) from both departments and across the University of Maryland's campus. GRAD-MAP began in 2013, when graduate students worked to develop a program to change the status quo in physics and astronomy. (Image: *GRAD-MAP founders: Dr. Ashlee Wilkins (left), Dr. Katie Jameson (center), and Dr. Alex McCormick (right).*)<br>
<br>

## Leads
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="120px" height="160px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
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


## Faculty Advisors
{% assign number_printed = 0 %}
{% for member in site.data.faculty_advisors %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive"  width="120px" height="160px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }}</i> <br> Role: {{ member.info }}
  <ul style="overflow: hidden">

  </ul>
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



## 2024 Research Mentors
{% assign number_printed = 0 %}
{% for member in site.data.faculty_mentors %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive"  width="120px" height="160px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }}</i> <br> Role: {{ member.info }}
  <ul style="overflow: hidden">

  </ul>
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

## Graduate Student Volunteers

{% assign number_printed = 0 %}
{% for member in site.data.student_volunteers %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive"  width="120px" height="160px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }}</i> <br> Role: {{ member.info }}
  <ul style="overflow: hidden">

  </ul>
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

# Past Leads and Mentors

#### We are grateful for the support given by the following people to GRAD-MAP either as a *graduate student*, a *postdoctoral associate*, or a *faculty member*:

## Leads
{% assign number_printed = 0 %}
{% for member in site.data.past_leads %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive"  width="120px" height="160px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }}</i> <br> Role: {{ member.info }}
  <ul style="overflow: hidden">

  </ul>
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

## Mentors and Volunteers
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Past Graduate Students</h4>
{% for member in site.data.past_volunteers %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Faculty Members</h4>
{% for member in site.data.past_mentors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Research and Outreach Staff</h4>
{% for member in site.data.past_staff %}
{{ member.name }}
{% endfor %}
</div>

</div>


