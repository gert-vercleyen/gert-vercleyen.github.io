---
layout: page
nav: true
title: Projects
permalink: /projects/
---

Here you can find some of my current projects.

## Implementing Anyonica's functionality in Julia. 
Anyonica has a huge number of useful functions for dealing with fusion categories and equations arising when computing properties
of these categories. It is a Mathematica package, however, which is non-free, closed source, and yes, slow when it comes to symbolic algebra. Therefore, I am implementing the current functionality of Anyonica in julia (with [OSCAR](https://www.oscar-system.org/)). 

### FusionRings
The first part of the project, a fusion rings package [FusionRings](https://github.com/anyonwiki/FusionRings/) developed with Sami Nasser Zagha, is almost finished and we expect to have a fully functioning, documented package with proper continuous integration by the end of the year.

### Lyctor
The package that will eventually replace Anyonica is [Lyctor](https://github.com/anyonwiki/Lyctor). The idea of Lyctor is to provide two sets of tools for dealing with Fusion categories: 
1. Tools for solving huge sparse systems of polynomial equations and equalities
2. Tools for probing properties of fusion categories


This package is still only in its concept phase and it will take some time to be functional, though.

## Expanding the capabilities of the AnyonWiki. 
The [wiki](https://anyonwiki.org) is far from finished and the I will keep working on it by adding more data and connections between data. 
