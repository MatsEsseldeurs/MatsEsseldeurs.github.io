---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>The fate of Earth during the Sun’s giant phases</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/Earth1.png" style="width:600px; min-width:34%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:5px;" align="right"/>

What will happen to the Earth when the Sun reaches the end of its life? In about five billion years, the Sun will leave the main sequence and expand into a red giant before eventually becoming a white dwarf. Whether the Earth survives these giant phases depends on the competition between two physical processes. As the Sun loses mass, the Earth's orbit expands. At the same time, tidal interactions transfer orbital energy and angular momentum, causing the Earth's orbit to shrink. Accurately modelling both effects is essential to predicting the long-term fate of our planet.

In this work, I combined stellar evolution models with a new, physically motivated description of tidal dissipation and updated prescriptions for stellar mass loss. Earlier studies generally concluded that the Earth would be engulfed during the Sun's red giant evolution. Our results show that the outcome is more nuanced: with the revised tidal model and observationally motivated mass-loss rates, the Earth is likely to narrowly escape engulfment. While the planet would survive dynamically, it would have become completely uninhabitable long before, having lost its oceans and atmosphere as the Sun's luminosity steadily increased.

Beyond the fate of the Earth, this research provides new insights into the orbital evolution of planets around evolved stars. By improving our understanding of tidal interactions and stellar mass loss, these models help interpret observations of planetary systems around red giants and white dwarfs, and contribute to a broader picture of how planetary systems evolve as their host stars age.

{% bibliography -f articles -q @*[earth=True]  %}
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>Orbital evolution of companions to AGB stars</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/OrbitalEvolution.png" style="width:380px; min-width:34%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:5px;" align="right"/>

Building on this framework, I apply these models to individual evolved systems to unravel their evolutionary history. One of the best examples is the nearby asymptotic giant branch (AGB) star π¹ Gruis, where high-resolution ALMA observations allowed us to directly measure the orbital motion of its close stellar companion. Combining these observations with models of stellar evolution and tidal interactions enabled us to reconstruct the system's orbital evolution and test long-standing theories of binary interactions.

Our analysis revealed that the companion follows an almost perfectly circular orbit. This was an unexpected result, as current models predict that the orbit should still retain a significant eccentricity at this stage of the AGB evolution. The observed orbit therefore points to more efficient tidal circularisation than predicted by existing theories, providing an observational constraints on tidal interactions in evolved stars.

Understanding systems such as π¹ Gruis is essential for improving models of binary evolution. These systems serve as natural laboratories for testing how tidal dissipation, stellar mass loss, and mass transfer shape stellar orbits. By confronting theoretical models with detailed observations, we can better predict the future evolution of evolved binaries and the planetary systems that orbit them.

{% bibliography -f articles -q @*[orbevol=True]  %}
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>Tidal Dissipation in Evolved Stars</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/tidal_dissipation.png" style="width:380px; min-width:34%; max-width:100%; margin-left:0px; margin-right:20px; margin-bottom:0px; margin-top:5px;" align="left"/>

The studies presented above rely on a detailed understanding of one of the key processes governing orbital evolution: tidal dissipation. As stars evolve, their internal structure changes dramatically, altering how efficiently tidal forces dissipate energy and exchange angular momentum with orbiting companions. These interactions determine whether planets and binary companions migrate outward, spiral inward, or are eventually engulfed by their host star.

To accurately model these effects, I developed ab-initio calculations of tidal dissipation that directly link the efficiency of tidal energy loss to the evolving internal structure of the star. Rather than relying on simplified prescriptions, this approach follows the tidal response throughout the entire evolution of low- and intermediate-mass stars, from the pre-main sequence to the white dwarf stage, providing a physically motivated description of tidal interactions across all evolutionary phases.

This framework forms the foundation for my research on the orbital evolution of planetary systems and binary stars. By combining stellar evolution with first-principles tidal modelling, it enables more reliable predictions of how companions respond to the dramatic changes their host stars undergo, from the main sequence through the giant phases and into their final stages of evolution.

{% bibliography -f articles -q @*[tides=True]  %}
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>3D simulations of AGB stellar winds</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/2Dplotrho_orbital2.png" style="width:400px; min-width:39%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:0px;" align="right"/>

My research began with investigating the winds of asymptotic giant branch (AGB) stars, a late stage in the lives of Sun-like stars during which they lose a large fraction of their mass. These stellar winds play a crucial role in enriching the interstellar medium with gas and dust, providing the raw material for future generations of stars and planets. High-resolution observations have revealed that these outflows are rarely spherical, instead displaying intricate spirals, arcs, and disks that are thought to arise through interactions with orbiting companions.

To better understand how these structures form, I developed three-dimensional hydrodynamical simulations of dust-driven AGB winds. By implementing a radiative transfer algorithm in the smoothed particle hydrodynamics (SPH) code Phantom, the simulations self-consistently account for how stellar radiation accelerates the wind and how the gravitational influence of a companion sculpts the outflow. I evaluated several radiative transfer prescriptions against detailed radiative transfer calculations, identifying an approach that accurately reproduces the wind dynamics while remaining computationally efficient.

These simulations provide a physically motivated framework for interpreting the complex morphologies observed around evolved stars. They improve our understanding of how binary companions shape stellar winds and lay the foundation for my later work on tidal interactions and the orbital evolution of planetary systems and binary stars around evolved stars.

{% bibliography -f articles -q @*[winds=True]  %}
</div>
</div>
