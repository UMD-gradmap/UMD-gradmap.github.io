---
title: "News"
layout: textlay
excerpt: "Graduate Resources Advancing Diversity with Maryland Astronomy and Physics (GRAD-MAP) at the University of Maryland."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br> {{ article.headline }}
{% endfor %}
