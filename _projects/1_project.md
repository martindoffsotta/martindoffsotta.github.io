---
layout: page
title: Energy management for hybrid-electric aircraft
description:
img: assets/img/hybrid1.png
importance: 1
related_publications: false
---

Hybrid-electric propulsion systems are a vital part of the technology roadmap for decarbonising the air transport industry. The commercial viability of such systems relies on onboard energy management. Through a convex formulation of mathematical models of the propulsion system of a hybrid-electric aircraft, a computationally tractable optimisation problem is constructed whose globally optimal solution is used to arbitrate in real time the power demand of the aircraft between the gas turbine and electric motor, allowing significant fuel savings. Both series and parallel hybrid-electric propulsion architectures are considered. Computation times are reduced by an order of magnitude compared to generic convex optimisation solvers like CVX thanks to a custom implementation of a first order solver (ADMM), enabling fast real-time implementations and reductions of in-flight CO2 emissions for new generations of more-electric aircraft.

Future research will consider the use of other types of hybrid-electric architectures based on fuel cells and liquid hydrogen gas turbines to meet the objectives of net zero emissions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hybrid1.png" title="Hybrid-electric propulsion" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Parallel hybrid-electric propulsion system.
</div>
