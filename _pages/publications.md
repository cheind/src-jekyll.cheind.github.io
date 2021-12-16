---
layout: page
permalink: /publications/
title: publications
description: Publications
years: [2021,2019,2018,2017,2016]
nav: false
published: false
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @inproceedings[year={{y}}]* %}
{% endfor %}

</div>
