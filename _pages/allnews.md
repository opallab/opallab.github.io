---
title: "News"
layout: textlay
excerpt: "OpAL Lab at University of Waterloo."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
