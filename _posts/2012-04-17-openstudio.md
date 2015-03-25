---
layout: post
title: First Impressions of <em>OpenStudio</em>
---

<em>OpenStudio</em> advertises itself as collection of software tools to support whole building energy ‘modeling’ (see <http://openstudio.nrel.gov>).

I like the fact that it is open source and that its plug-in architecture allows the use of <em>EnergyPlus</em> (whole building energy simulation) together with <em>Radiance</em> (claimed to be the gold standard for accurate lighting simulation) – a combination that I have not seen before. I also like the way it sets up a UNIX-style toolchain from weather data to 3D model to zones and systems through to simulation and results. I am intrigued by the possibility of high level access using <em>R</em> (particularly) or perhaps <em>Python</em>, even <em>Ruby</em> (yet another programming language to learn !) or <em>C++</em> and <em>C#</em> (no thanks…).

I wonder how the building designer can navigate through such a simulation workflow? One of the developers stated in a presentation at the <em>International Radiance Workshop 2011</em>, Berkeley that

> Workflows must be well documented and clearly explained in a way that eliminates mystery and compels users to action

but I do not feel that this is the case with <em>OpenStudio</em> at the moment (although to be fair the version number is only 0.7.0).

The other question I have, having never run such a simulation before, is the question of scale. If I modelled a domestic house on the one hand and the <em>Shard</em> on the other, could I be truly be confident about the validity of such simulations?
