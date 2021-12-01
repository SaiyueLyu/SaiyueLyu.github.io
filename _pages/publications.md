---
layout: page
permalink: /publications/
title: publications
description: looking forward to my first publication:)
#years: [1956, 1950, 1935, 1905]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">
  
One first author paper submitted to WWW'22 that is under review. 

#{% for y in page.years %}
  #<h2 class="year">{{y}}</h2>
  #{% bibliography -f papers -q @*[year={{y}}]* %}
#{% endfor %}

</div>
