---
layout: page
permalink: /publications/
title: publications
subtitle: Publications
description: Publications in reversed chronological order.
# Todo: Filter by categories and order
nav: true
nav_order: 1
---

Go to [Full List Publications](#full-list-of-publications)

<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>

## Full List of publications

{% assign sorted_publications = site.data.publications | sort: 'year' | reverse %}

{% assign current_year = nil %}

{% for publi in sorted_publications %}
  {{ forloop.index }}. <strong>{{ publi.title }}</strong> <br />
  <em>{{ publi.authors }} </em> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

