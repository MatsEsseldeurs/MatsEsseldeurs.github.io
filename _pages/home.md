---
title: "Home"
layout: default
sitemap: false
permalink: /
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>


<div id="homeid" class="col-sm-12 col-xs-12">
<figure>
  <img src="{{site.url}}{{site.baseurl}}/images/headshot.jpg" style="width:350px; min-width:30%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:0px;" align="right">
</figure>

<div style="text-align:justify">
### Welcome to my personal website!

I'm Mats Esseldeurs, a PhD student at [KU Leuven](https://www.kuleuven.be/kuleuven/)'s [Institute of Astronomy](https://fys.kuleuven.be/ster), in the team of [Prof. Dr. Leen Decin](https://fys.kuleuven.be/ster/staff/senior-staff/leen-decin). My research interests lie at the intersection of math, physics, and computer science, where I am fascinated by the complex phenomena that shape our universe.

Accademically, I am particularly interested in:
* <b>Radiative transfer in 3D fluid dynamics</b> — exploring efficient ways to approximate radiative transfer in simulations, especially in the context of the cool outflows of AGB stars.
* <b>Tidal dissipation in binary systems</b> — using semi-analytical modeling to understand how strong tidal forces drive the orbital evolution of stars and planets over time.
* <b>Orbital evolution simulations</b> — investigating the dynamical evolution of binary and planetary systems through computational modeling, particularly focusing on the effects of tides and mass loss, bringing together my interests in fluid dynamics and tidal interactions.

I am also passionate about science communication and education. I enjoy sharing knowledge, whether as a tutor in mathematics and physics, a teaching assistant at KU Leuven, or a supervisor of Master's theses.

Outside of research, I love cycling in the Belgian countryside, listening to science fiction audiobooks, and watching nature documentaries. I also enjoy spending time with friends and family, experimenting with new recipes, and exploring the vibrant city of Leuven.

Thanks for visiting my website! Feel free to get in touch if you have any questions or comments.
</div>


<div class="jumbotron">
### Selected Publications
{% bibliography -f articles -q @*[selected=True]  %}
</div>