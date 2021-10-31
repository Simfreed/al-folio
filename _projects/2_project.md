---
layout: page
title: Agent-based Simulation
description: 
img: /assets/img/afines_schem.jpg
importance: 2
category: work
---

For many systems in biology, the basic molecular interactions are well understood, but the way they modulate larger phenomena are still, well, phenomenal.
An example is the actomyosin cytoskeleton, a network of semiflexible actin filaments, myosin motors, and crosslinker proteins that provide cells with multiple functions and attributes, such as their shape, ability to propagate forces, and intracellular transport.
The fundamental interactions are well understood -- for example, a myosin motor can bind onto an actin filament, and walk unidirectionally toward its end, and crosslinkers can bind multiple filaments together, but connecting these pairwise interactions to larger scale collective behavior is not immediately apparent. 
To determine how these interactions led to larger scale biophysics, I [developed and benchmarked](https://www.sciencedirect.com/science/article/pii/S0006349517306227) an agent-based computational framework, [AFINES](github.com/simfreed/afines) (Active Filament NEtwork Simulation) , and explored the meso-scale consequences of interactions between molecular constituents.
I found the [basic ingredients of structures and mechanisms](https://pubs.rsc.org/en/content/articlehtml/2018/sm/c8sm00741a?casa_token=FFfOEq97Y6AAAAAA:EfXtqtr6sAF6bZFXrA3_Yn265vDsGWv4_gHLlP8C2AY4KZ2fzIl-DIzhxL24kvmQlmkPr4w7VyO9GnW_), such as bundled and contracted networks (movies below) as well as new mecahanisms that could yield [contraction of networks with rigid rods](https://www.pnas.org/content/114/47/E10037?collection=&utm_source=TrendMD&utm_medium=cpc&utm_campaign=Proc_Natl_Acad_Sci_U_S_A_TrendMD_1), in collaboration with the Gardel lab (UChicago) and [crosslinker domain formation](https://www.pnas.org/content/116/33/16192.short) in collaboration with the Kovar, Voth, and Hocky labs. 

<div class="row no-gutters">
    <div class="col-sm mt-3 mt-md-0">
    <iframe width="250" height="250" src="https://www.youtube.com/embed/OQuEmLr8LJY" title="Bundling" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="col-sm mt-3 mt-md-0">
<iframe width="250" height="250" src="https://www.youtube.com/embed/PaPEY7mDAFk" title="Polarity Sorting" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="col-sm mt-3 mt-md-0">
<iframe width="250" height="250" src="https://www.youtube.com/embed/LIt14vw3yh0" title="Contracting" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>

Broadly, I am very interested in developing agent-based simulations, and carefully simulationg dynamical systems, to deduce if, when, and how small scale interactions yielded larger scale phenomena. 
I am also specifically interested in using AFINES, together with 3D force inference methods, to understand the mechanics behind morphogenesis, and how structures form in crowded cellular environments.
