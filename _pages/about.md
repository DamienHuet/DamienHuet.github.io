---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a {{site.author.occupation}} at {{site.author.institution}}{% if site.author.location_short %}, in the beautiful city of {{site.author.location_short}}{% endif %}. Under the supervision of Prof. Anthony Wachs, my reserch interests pertain to the numerical simulations of biological capsules in capillary vessels, as well as simulations of entangled granular media.

---

Granular dynamics
======
I have implemented an accurate contact law for the simulations of granular materials made of arbitrary-shaped particles. This allows the use of our high-fidelity simulations to gain insight on complex granular phenomena, such as entanglement during dynamic processes.  
The movie below shows how our simulations of cross-shaped particles compares with experiments. The qualitative agreement is very satisfactory (and the quantitative agreement too, as shown in the [associated publication](/publications/2021-10-08-granular-avalanches-of-entangled-rigit-particles.pdf)).
<iframe width="560" height="315" src="https://www.youtube.com/embed/yzlzn_XrkJA?autoplay=1&loop=1&controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

---

Biological flows
=====
I am currently working on a fully Eulerian framework for the simulations of elastic membranes surrounded by viscous fluids. This topic is highly relevant to biological flows, since a Red Blood Cell (RBC) is nothing else than a droplet of viscous fluid (hemoglobine) surrounded by a lipid-bilayer membrane, and immersed in blood plasma. My code relies on the multiphase flow solver [Basilisk](http://www.basilisk.fr) and is fully open-source.  
The movie below represents an elastic capsule deforming under the action of a shear flow. Colour represents x-velocity. I can't cease to be amazed by the beautiful adaptive mesh provided by Basilisk!
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZDsvt4Ej_0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
