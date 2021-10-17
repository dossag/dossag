---
title: "News"
layout: textlay
excerpt: "Dossa personal Website at [XTBG](http://en.xtbg.ac.cn/)."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
