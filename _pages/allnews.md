---
title: "News"
layout: textlay
excerpt: "Ménard Lab Lab at University of Ottawa."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
