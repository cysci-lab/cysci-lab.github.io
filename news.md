---
title: "News"
layout: textlay
excerpt: "CySci Lab at UTEP."
sitemap: false
permalink: /news/
---

# News

{% for article in site.data.news %}
<p><b>{{ article.date }}</b> <br>
<em>{{ article.headline }}</em></p>
{% endfor %}