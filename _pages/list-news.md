---
layout: gridlay
title: News
sitemap: false
permalink: /list-news.html
---


{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}