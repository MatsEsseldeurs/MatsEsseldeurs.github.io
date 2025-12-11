---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>3D simulations of AGB stellar winds</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/2Dplotrho_orbital2.png" style="width:400px; min-width:39%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:0px;" align="right"/>

In my research, I focus on understanding the behavior of stars during the Asymptotic Giant Branch (AGB) phase, which is a crucial stage in their evolution. During this phase, stars with an initial mass below approximately 8 solar masses develop a strong stellar wind due to radiation pressure on newly formed dust grains.

Recent observations have shown that AGB outflows display significant morphological complexities, which are most likely caused by the interaction with a companion. In order to better understand and describe these morphologies, I have developed 3D simulations of AGB stellar winds.

My simulation takes into account both the radiation force in dust-driven winds and the impact of a companion on the AGB wind morphology. To achieve this, I have implemented a ray-tracer for radiative transfer in the smoothed particle hydrodynamics (SPH) code Phantom. This method allows for the creation of a 3D map of the optical depth around the AGB star.

I have compared the effects of four different prescriptions of radiative transfer, with different degrees of complexity, including the free-wind, the geometrical, the Lucy, and the attenuation prescription. By comparing the results to predictions from the 3D radiative transfer code Magritte, I have found that the Lucy prescription provides the most accurate results for most of the model, although it does not account for all effects.

Overall, my research highlights the critical role of the radiation force in dust-driven AGB winds, impacting the velocity profile and morphological structures. These findings provide important insights into the behavior of stars during the AGB phase and contribute to our understanding of the evolution of stars.

{% bibliography -f articles -q @*[winds=True]  %}
</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>Tidal Dissipation in Evolved Stars</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/tidal_dissipation.png" style="width:380px; min-width:34%; max-width:100%; margin-left:0px; margin-right:20px; margin-bottom:0px; margin-top:5px;" align="left"/>

Building on our understanding of AGB stellar winds, we turn to the crucial process of tidal dissipation in evolved stars. As these stars expand and develop deep convective envelopes, their interactions with orbiting companions become dominated by tidal forces. These tides can transfer angular momentum, leading to dramatic changes in the orbits of planets and binary companions.

To accurately capture these effects, we employ ab-initio modelling of tidal dissipation, directly linking the internal structure and evolution of the star to the efficiency of tidal energy loss. By moving beyond simplified prescriptions and instead using detailed stellar models, we can quantify how convection, oscillations, and the changing stellar envelope shape the tidal response.

This physically motivated approach allows us to accurately predict how tidal interactions influence the fate of companions: whether they spiral in and are engulfed, or survive as the star evolves. Our ab-initio tidal dissipation models thus provide the essential bridge between the physical processes in evolved stars and the orbital evolution of their planetary systems, setting the stage for understanding the diverse outcomes observed in post-AGB systems.

{% bibliography -f articles -q @*[tides=True]  %}
</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>Orbital evolution of companions to AGB stars</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/OrbitalEvolution.png" style="width:380px; min-width:34%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:5px;" align="right"/>

In addition to simulating the winds of AGB stars and modelling their internal tidal dissipation, I investigate how these processes together shape the orbits of planets and companions. The significant mass-loss and structural changes during the AGB phase, combined with strong tidal forces, can dramatically alter the fate of any objects in orbit. Whether a companion survives, spirals inward and is engulfed, or escapes to a wider orbit depends on the delicate balance between tidal dissipation, mass-loss, and accretion processes.

Our research advances the field by combining ab-initio tidal dissipation calculations with detailed 3D hydrodynamic simulations of the wind and the gravitational influence of companions. This comprehensive approach allows us to accurately model not only the mass-loss rates and accretion efficiency, but also the evolving tidal forces that govern orbital evolution.

By integrating these effects, we can build coherent models of planetary systems around evolved AGB stars, providing new insights into the survival of planets, the formation of close binaries, and the diversity of systems observed around white dwarfs and post-AGB stars.

{% bibliography -f articles -q @*[orbevol=True]  %}
</div>
</div>
