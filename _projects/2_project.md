---
layout: page
title: Difference of convex functions in nonlinear robust MPC
description:
img: assets/img/DC1.png
importance: 2
---

Robust model predictive control (MPC) is concerned with preserving performance and closed-loop stability for systems subject to uncertainty, while offering the properties of optimality, real-time tractability and constraint satisfaction of classical MPC. This approach is promising in air transport scenarios where robustness, efficiency and safety are vital requirements. However, a direct application of robust MPC methods to realistic nonlinear problems requires the solution of numerically intractable optimisation.

In this research, robust MPC is made computationally tractable for nonlinear systems representable as a difference of convex (DC) functions. The approach is based on successively linearising the system around guess trajectories and treating the linearisation error as a bounded disturbance in a robust optimisation framework. Crucially, by convexity of the dynamics, the linearisation error is necessarily convex and takes its maximum at the boundary of the uncertainty set, allowing tight bounds to be computed. This provides a very general method for solving uncertain optimisation problems as a sequence of computationally tractable convex programs where the dynamics are approximated tightly by a set of convex inequalities. This convex optimisation is then leveraged in a robust MPC framework.

The approach can be applied to any continuous nonlinear system for which a DC decomposition can always be computed. Techniques such as sums-of-squares polynomials, deep neural networks, and machine learning can be used to learn the nonlinear dynamics in DC form. The expected outcome of this research will be the systematic synthesis of safe, robust, computationally efficient and optimal controllers for safety-critical applications.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DC1.png" title="DC decomposition" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DC2.png" title="DC decomposition" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left: learning system dynamics in DC form with radial basis functions. Right: DC decomposition with recurrent neural networks. 
</div>
