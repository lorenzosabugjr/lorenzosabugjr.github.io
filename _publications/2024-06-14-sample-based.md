---
title: "Sample-Based Trust Region Dynamics in Contextual Global Optimization"
collection: publications
category: manuscripts
permalink: /publication/2024-06-14-sample-based
excerpt: 'It really helps to consider the context to further improve the performance of a black-box optimization method.'
date: 2024-06-14
venue: 'IEEE Control Systems Letters (L-CSS)'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://doi.org/10.1109/LCSYS.2024.3414970'
citation: 'L. Sabug, L. Fagiano and F. Ruiz, &quot;Sample-Based Trust Region Dynamics in Contextual Global Optimization,&quot; in <i>IEEE Control Systems Letters</i>, vol. 8'
---

The problem of contextual global optimization is treated, in which a generally non-convex scalar objective (possibly black-box) depends not only on the decision variables, but also on uncontrollable, observable context variables. Assuming Lipschitz continuity of the objective function with respect to its arguments, the proposed approach builds a Set Membership model from observed samples. According to the observed context, a submodel that relates the objective to the decision variables is isolated, and used by a zeroth-order technique to pick the appropriate decision variable for sampling. A novel trust region dynamic is introduced, adjusting its size with samples instead of iterations. Such a technique makes the resulting contextual optimization algorithm more flexible with respect to the context behavior, whether it is changing smoothly, abruptly, or a combination of both. Benchmark tests and a case study demonstrate the efficacy of the proposed method.