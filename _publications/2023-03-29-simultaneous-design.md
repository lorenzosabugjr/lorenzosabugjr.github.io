---
title: "Simultaneous Design of Passive and Active Spacecraft Attitude Control Using Black-Box Optimization"
collection: publications
category: manuscripts
permalink: /publication/2023-03-29-simultaneous-design
excerpt: 'We use black-box optimization to approach a difficult engineering design problem for a spacecraft.'
date: 2023-03-29
venue: 'Control Engineering Practice'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://doi.org/10.1016/j.conengprac.2023.105516'
citation: 'L. Sabug, G.P. Incremona, M. Tanelli, F. Ruiz, and L. Fagiano, &quot;Simultaneous design of passive and active spacecraft attitude control using black-box optimization,&quot; in <i>Control Engineering Practice</i>, vol. 135'
---

This paper investigates the simultaneous design of active attitude control and passive attitude compensation mechanism for a spacecraft to satisfy practically-motivated mission objectives and constraints. The expressions of these fitness-related metrics with respect to the design variables are not analytically available, due to the nontrivial interactions between the spacecraft components and the interactions with the environment. Thus, such functions can only be approximately learned from data derived from simulations. We approach this difficult design problem using a black-box optimization (BBO)-based approach, which combines learning and optimizing the objective and constraint functions by design of experiments. The proposed BBO-based approach is assessed in the context of a 3U CubeSat system design with both a passive magnetic attitude compensation and an active reaction wheel-based control, tested on a simulator considering orbital and environmental dynamics. Simulation results and statistical tests compared to other design methods show the capability of the BBO-based approach to provide a design with the best tracking performance while at the same time satisfying ground station communication requirements and power budget.