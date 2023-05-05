---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a {{site.author.occupation}} at {{site.author.institution}}{% if site.author.location_short %}, in the beautiful city of {{site.author.location_short}}{% endif %}. My reserch interests pertain to applied mathematics and high-performance scientific computing: in particular, I develop numerical methods applied to various applications, ranging from numerical simulations of granular dyanamics to finding solutions to complex nonlinear Partial Differential Equations (PDEs) in the context of biological flows.

---

Biological flows
=====
I have implemented a solver for elastic membranes surrounded by viscous fluids. This topic is highly relevant to biological flows, since a Red Blood Cell (RBC) is nothing else than a droplet of viscous fluid (hemoglobin) surrounded by an elastic membrane (a lipid bilayer), and immersed in blood plasma. My code relies on the multiphase flow solver [Basilisk](http://www.basilisk.fr) and is [fully open-source](http://basilisk.fr/sandbox/huet/README). My code is developed using coding best practices, and undergoes rigorous tests that are also fully open source.
The movie below represents an elastic capsule deforming while it flows through a constricted channel. Colour represents the x-component of the fluid velocity.
<p align="center">
<iframe width="1200" height="300" src="https://www.youtube-nocookie.com/embed/PH_RgW8Y39Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

Below is another example of the adaptive front-tracking solver for elastic membranes that I develop. Two initially spherical membranes are placed in a shear flow and we witness their interception. The color field represents the vertical component of the velocity.
<iframe width="560" height="315" src="https://www.youtube.com/embed/TiHKCAAelV4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

Granular dynamics
======
I have implemented an accurate contact law for the simulations of granular materials made of arbitrary-shaped particles. This allows the use of our high-fidelity simulations to gain insight on complex granular phenomena, such as entanglement during dynamic processes.  
The movie below shows how our simulations of cross-shaped particles compares with experiments. The qualitative agreement is very satisfactory (and the quantitative agreement too, as shown in the [associated publication](/publications/2021-10-08-granular-avalanches-of-entangled-rigit-particles.pdf)).
<iframe width="560" height="315" src="https://www.youtube.com/embed/yzlzn_XrkJA?autoplay=1&loop=1&controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  
