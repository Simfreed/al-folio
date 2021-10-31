---
layout: page
title: Developmental Bifurcations
description:
img: /assets/img/bifurc_preview.jpg
importance: 1
category: work
---
An individual animal is made up of many different kinds of cells, from neurons to gametes, and exhibits significant geometric asymmetry, in having, for example, a head at one end and feet at the other. 
Yet, all animals start as a single, mostly symmetric cell: a fertilized egg that has the functional potential to produce any cell type (pluripotent) and to induce the shape changes necessary to yield its matured, complex geometry. 
The past century of developmental biology research has distinguished cell types and identified molecules that induce them, but the dynamic processes through which cells commit to specific fates and establish robust spatial patterns are not well understood. 

<p align="center">
<iframe width="420" height="200" src="/assets/img/toy_pot_dat.mp4" frameborder="0" allowfullscreen></iframe>
</p>

<div class="caption" fontsize=4px style="text-align:justify">
Qualitative changes in the underlying geometry (i.e., bifurcations) of a dynamical system can be detected via the variance (or covariance, for nD systems) of state variables. 
</div>
I am applying concepts from dynamical systems theory to big biological data to bridge the scales between cell fate and molecular mechanism.
I have recently shown how bifurcations -- the signature of fundamental change in classical, physical dynamical systems, like a beam buckling, or a power-line network crashing- can be detected during development from single-cell RNA-seq data. 
Moreover, information about the underlying dynamical system guiding the transition, which is normally hidden, because it operates at a faster timescale than we can measure, is inferrable from the data. 
I am currently working to push this research further from multiple angles, by studying bifurcations during morphogenesis and using simple models to determine if we can predict the results of developmental perturbation experiments directly from gene expression data.
<div class="row justify-content-sm-center">
        <img class="img-fluid rounded z-depth-1" width="1000" src="{{ '/assets/img/neut_traj.jpg' | relative_url }}" alt="" title="Bifurcation analysis example"/>
</div>
<div class="caption" fontsize=4px style="text-align:justify">
        Bifurcation detection can be applied to characterize the mechanisms guiding a developmental bifurcation. 
        In this example of a single-cell RNA-seq trajectory for Neutrophil cells (first published in 
        <a href="https://www.science.org/doi/10.1126/science.aaw3381">Weinreb et. al., Science, 2020</a>) (A), we've detected both one-to-many (tau_d) and one-to-one (tau_m) bifurcations (B), mapped them onto a cell-fate decision and a maturation point in development (C), and used the correlation matrix at the maturation bifurcation to infer the genetic regulation that guides the transition (D). For more details, see 
        <a href="https://www.biorxiv.org/content/10.1101/2021.05.03.442465v1">Freedman et al., biorXiv 2021</a>. 
</div>


