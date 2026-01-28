---
layout: page
nav: true
title: Projects
permalink: /projects/
---

Here you can find some of my current projects.

## Implementing Anyonica's functionality in Julia. 
Anyonica has a huge number of useful functions for dealing with fusion categories and equations arising when computing properties
of these categories. It is a Mathematica package, however, which is non-free, closed source, and yes, slow when it comes to symbolic algebra. Therefore, I am implementing the current functionality of Anyonica in julia (with [OSCAR](https://www.oscar-system.org/)). The first part of the project, a fusion rings package [FusionRings.jl](https://github.com/gert-vercleyen/FusionRings.jl ) is under development with Sami Nasser Zagha.

## Expanding the capabilities of the AnyonWiki. 
The wiki is far from finished. On the one hand, we plan to extend the
data it contains. In particular, we will add
* centers of multiplicity-free fusion categories (every center of multiplicity-free fusion categories up to rank 5 has already been constructed by F. Maurer and U. Thiel using their TensorCategories.jl package, and more are being computed at the moment)
* an individual page for each multiplicity-free fusion category up to rank 7. Each page will contain core information about the category such as references to the literature where the category is used, a download link for the complete set of F-symbols, R-symbols and pivotal coefficients, and standard quantities that are of interest such as the quantum dimensions, modular data (if applicable), the basis gauge invariants, the minimal field of definition, info on whether the category is braided, unitary, spherical, ribbon, and or modular. (Note that all computable data has already been computed)
* the full database of fusion rings (>28000 rings), including those with multiplicity and all multiplicity-free rings up to rank 10. (This data is already computed and is partly available via the Anyonica package)
* lists of small invariants that allow one to recognize (and distinguish) the stored fusion categories
* bimodule categories,
* G-braidings,
* bicrossed products of categories,
* Zestings of categories,
* vertex operator algebras,
* info on modular isotopes,
* algebra objects
* nim-reps of fusion rings

On the other hand, we want to add functionality that researchers
requested. In particular:
* We will incorporate all data in a relational database. This allows researchers to search for categories and rings with specific properties, but also to reveal connections between categories and the data used to represent them.
* Researchers will be able to log in using ORCID and add information to pages such as references to literature where specific structures are used. Likewise, researchers will be able to add pages of documentation and info on properties of fusion rings and categories. Researchers will be able to connect a GitHub account to track their contributions. This way, anyone who desires can get some recognition for the work they do on the wiki.
