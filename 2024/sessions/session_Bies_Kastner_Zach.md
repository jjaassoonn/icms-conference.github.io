---
layout: session
title: "Classical Algebraic Geometry & Modern Computer Algebra: Innovative Software Design and its Applications"
---
### Organizers
   * [Martin Bies (RPTU Kaiserslautern, Germany)](https://martinbies.github.io/)<br/>
   * [Lars Kastner (TU Berlin, Germany)](https://lkastner.github.io/)<br/>
   * [Matthias Zach (RPTU Kaiserslautern, Germany)](https://github.com/HechtiDerLachs)<br/>

### Aim and Scope

Recent years have shown new applications of symbolic methods in computer algebra at scale. For instance, previously deemed impossible classification algorithms from toric and tropical geometry result in terabyte sized data sets. This calls for the development of new algorithms, allowing --for example-- for parallelization, but also new high level user interfaces. The aim is to bring together experts in computational algebraic geometry and those who want to use newly provided methods and algorithms in their research endeavors. We encourage speakers to highlight the computational aspects of their work and to augment their presentation with code examples. Our focus includes valuable application of these methods in physics, particularly in string theory and F-theory.

## Accepted Talks

   * [Simon Felten](https://simon-felten.github.io/) (Columbia University)
   * [Yang-Hui He](https://www.physics.ox.ac.uk/our-people/he) (London Institute for Mathematical Sciences)
   * [Patrick Jefferson](https://inspirehep.net/authors/1274984) (Massachusetts Institute of Technology)
   * [Chiara Meroni](https://merochia.wixsite.com/chiara-meroni) (ETH Zurich)
   * [Giosuè Muratore](https://sites.google.com/view/giosue-muratore/home-page) (Universidade de Lisboa)
   * [Luca Remke](https://www.idsr.uni-stuttgart.de/en/institute/Remke/) (University of Stuttgart)
   * [Andrew P. Turner](https://apturner.net/) (University of Pennsylvania)

## Abstracts

### Localization in Gromov--Witten theory of toric varieties in a computer algebra system

#### Giosuè Muratore (Universidade de Lisboa)

Atiyah--Bott localization formula is a powerful tool for calculating the degree of equivariant classes of the moduli space of rational stable maps $\overline{M}_{0,n}(X,\beta)$, where $X$ denotes a smooth toric variety, $n$ is a non negative integer, and $\beta$ is an effective $1$-cycle. Implementation of the formula entails intricate computational challenges, involving graph theory, colorations, partitions, and other discrete objects. Furthermore, the computed solution is a large summation of rational numbers, underscoring the imperative nature of computational efficiency. This formula has been applied in very specific cases for computing Gromov--Witten invariants, addressing enumerative problems, and determining the small quantum ring of $X$, among other applications. 

A comprehensive implementation as a Julia package has been recently presented by the author.We show the features of the package with a particular emphasis to the noteworthy contribution of the package \verb!Oscar.jl!. Finally, we delve into the fundamental prerequisites for extending the implementation to encompass Algebraic GKM Manifolds.


### Exceptional sequences of line bundles on toric varieties

#### Luca Remke (University of Stuttgart)

We want to investigate whether every maximal exceptional sequence of line bundles is full for a smooth projective toric variety, given the existence of a full exceptional sequence of line bundles. This property has already been proved for toric varieties of Picard ranks 1 and 2. We therefore turn our attention to toric varieties of Picard rank 3, focusing on the del Pezzo surface of degree 7.