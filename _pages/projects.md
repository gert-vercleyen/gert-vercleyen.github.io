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
The first part of the project, a fusion rings package [FusionRings](https://github.com/gert-vercleyen/FusionRings.jl ) is under development with Sami Nasser Zagha and we expect to have a fully functioning, documented package with proper continuous integration by the end of the year.

### Lyctor
The package that will eventually replace Anyonica is [Lyctor](https://github.com/anyonwiki/Lyctor). The idea of Lyctor is to provide two sets of tools for dealing with Fusion categories: 
1. Tools for solving huge sparse systems of polynomial equations and equalities
2. Tools for probing properties of fusion categories


This package is still only in its concept phase and it will take some time to be functional, though.


## Expanding the capabilities of the AnyonWiki. 
The wiki is far from finished. On the one hand, we plan to extend the
data it contains. In particular, we will add
* centers of multiplicity-free fusion categories. Every center of multiplicity-free fusion categories up to rank 5 has already been constructed by F. Maurer and U. Thiel using their TensorCategories.jl package, and more are being computed at the moment.
* We already have an individual page for each multiplicity-free fusion category up to rank 7 but we will add more info to the pages. In particular:
    * a basis for gauge invariants,
    * (pivotal) (braided) tensor auto-equivalences (both the group and the actual transforms on the level of the symbols)
    * minimal fields of definition for F-, R-, P-symbols and any combination of these together with a list of F-, R-, and P-symbols in their minimal field
    * decompositions into smaller categories via, e.g., the Deligne product or the bicrossed product
    * relations to other categories via zesting and Morita equivalence
* lists of small invariants that allow one to recognize (and distinguish) the stored fusion categories
* bimodule categories,
* G-braidings,
* vertex operator algebras,
* info on modular isotopes,
* algebra objects and nim-reps of fusion rings
* etale and condensable algebras
* number fields and Galois groups of characters
* modular data up to rank 12 

On the other hand, we want to add functionality that researchers
requested. In particular:
* an advanced search bar that allows one to search for fusion rings/categories based on their properties.
  
