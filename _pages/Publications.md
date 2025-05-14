---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2022]
---

<div class="jumbotron">

### First author publications
{% bibliography -f articles -q @*[firstauthor=True && selected!=True] %}

### Thesis
{% bibliography -f thesis --query @thesis %}

### Co-author publications
{% bibliography -f articles -q @*[firstauthor!=True && selected!=True] %}



</div>