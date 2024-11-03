---
title: "News"
layout: textlay
excerpt: "Graduate Resources Advancing Diversity with Maryland Astronomy and Physics (GRAD-MAP) at the University of Maryland."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<i>{{ article.date }}</i> <br> <b>{{ article.headline }}</b> <br><br> {{ article.shortdesc }}
{% endfor %}
