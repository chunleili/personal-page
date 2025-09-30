---
title: "MGPBD: A Multigrid Accelerated Global XPBD Solver"
collection: publications
category: manuscripts
permalink: /publication/2025-08-14-MGPBD-number-2
date: 2025-08-14
venue: 'TVCG'
# slidesurl: 'https://github.com/chunleili/nonNewtonPaper'
paperurl: 'https://arxiv.org/abs/2505.13390'
# bibtexurl: 'http://chunleili.github.io/personal-page/files/NonNewton.bib'
code: 'https://github.com/chunleili/mgpbd'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
We introduce a novel Unsmoothed Aggregation (UA) Algebraic Multigrid (AMG) method combined with Preconditioned Conjugate Gradient (PCG) to overcome the limitations of Extended Position-Based Dynamics (XPBD) in high-resolution and high-stiffness simulations. While XPBD excels in simulating deformable objects due to its speed and simplicity, its nonlinear Gauss-Seidel (GS) solver often struggles with low-frequency errors, leading to instability and stalling issues, especially in high-resolution, high-stiffness simulations. Our multigrid approach addresses these issues efficiently by leveraging AMG. To reduce the computational overhead of traditional AMG, where prolongator construction can consume up to two-thirds of the runtime, we propose a lazy setup strategy that reuses prolongators across iterations based on matrix structure and physical significance. Furthermore, we introduce a simplified method for constructing near-kernel components by applying a few sweeps of iterative methods to the homogeneous equation, achieving convergence rates comparable to adaptive smoothed aggregation (adaptive-SA) at a lower computational cost. Experimental results demonstrate that our method significantly improves convergence rates and numerical stability, enabling efficient and stable high-resolution simulations of deformable objects.