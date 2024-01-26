---
title: "Manifold Optimization for Data Driven Reduced-Order Modeling"
collection: publications
permalink: /publication/2023-11-14-manifoldopt_ddROM
excerpt: 'This paper develops a Grassmannian algorithm to optimize orthogonally projected reduced-order models.'
date: 2023-11-14
venue: '2023 59th Annual Allerton Conference on Communication, Control, and Computing (Allerton)'
paperurl: 'https://ieeexplore.ieee.org/document/10313500'
citation: 'R. Newton, Z. Du, L. Balzano and P. Seiler, &quot;Manifold Optimization for Data Driven Reduced-Order Modeling,&quot; <i>2023 59th Annual Allerton Conference on Communication, Control, and Computing (Allerton) </i>, Monticello, IL, USA, 2023, pp. 1-6, doi: 10.1109/Allerton58177.2023.10313500.'
---
The focus of this paper is on data-driven reduced-order modeling. We assume a high fidelity, discrete-time model is available for simulation. The simulator allows state and output trajectories to be collected for any specified initial condition and input signal. An optimal reduced-order model (ROM) requires: (i) the selection of a lower dimensional subspace for the state of the ROM, and (ii) an optimal reduced-order state-space model (evolving on the lower dimensional subspace). A common heuristic is to: (i) select the lower-order subspace using proper orthogonal decomposition (POD), and (ii) use least-squares to fit the reduced-order state-space model on the POD subspace. We demonstrate the potential deficiencies of this heuristic via two simple examples. In order to address these deficiencies, we propose a novel method to optimize the choice of subspace using the Grassmann manifold. Finally, we show that our proposed manifold optimization empirically outperforms the POD heuristic on the two motivating examples and a planar wind farm model.

[Download paper here](https://ieeexplore.ieee.org/document/10313500)
