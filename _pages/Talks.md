---
title: "Presentations & Posters"
layout: gridlay
sitemap: false
permalink: /talks/
---

<!-- <div class="jumbotron">
### Upcoming Talks
{% bibliography -f conferences --query @upposter %}
</div> -->


<div class="jumbotron">

### Seminars
{% bibliography -f conferences -q @seminar %}

### Invited talks
{% bibliography -f conferences -q @conferencepres[invited=True] %}

### Contributed talks
{% bibliography -f conferences -q @conferencepres[invited!=True && poster_pres!=True] %}

### Posters
{% bibliography -f conferences -q @conferencepres[poster_pres=True]%}
</div>

