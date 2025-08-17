---
title: "News"
layout: textlay
excerpt: "WatCL Lab at University of Waterloo."
sitemap: false
permalink: /allnews.html
---

# News

### Recent Updates

{% for article in site.data.news %}
- **{{ article.date }}**: {{ article.headline }}
{% endfor %}
