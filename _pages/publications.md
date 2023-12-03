---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

16. (Under review) M.F.P. ten Eikelder, D. Schillinger, <br>
The divergence-free velocity formulation of the consistent Navier-Stokes Cahn-Hilliard model with non-matching densities, divergence-conforming discretization, and benchmarks, <br>
<a href="https://arxiv.org/abs/2311.09966">https://arxiv.org/abs/2311.09966</a>, 2023 <br>
<br>
15. (Under review) M.L. Mika, M.F.P. ten Eikelder, D. Schillinger, R.R. Hiemstra, <br>
Matrix-free polynomial preconditioning of saddle point systems using the hyper-power method <br>
https://arxiv.org/abs/2311.06926, 2023 <br>
<br>
14. (Under review) A. Ebrahem, M.F.P. ten Eikelder, <br>
T. Gangwar, M.L. Mika, D. Schillinger, Connecting continuum poroelasticity with discrete synthetic vascular trees for modeling liver tissue <br>
https://arxiv.org/abs/2306.07412, 2023 <br>
<br>
13. (Under review) M.F.P. ten Eikelder, K.G. van der Zee, D. Schillinger, <br>
Thermodynamically consistent diffuse-interface mixture models of incompressible multicomponent fluids, <br>
https://arxiv.org/abs/2302.09287, 2023 <br>
<br>
12. (Under review) J. Lotz, M.F.P. ten Eikelder, I. Akkerman, <br>
A space-time framework for periodic flows with applications to hydrofoils, <br>
https://arxiv.org/abs/2211.10964, 2022 <br>
<br>
11. M.F.P. ten Eikelder, S.K.F. Stoter, Y. Bazilevs, D. Schillinger, <br>
Constraints for eliminating the Gibbs phenomenon in finite element approximation spaces, <br>
Mathematical Models and Methods in Applied Sciences (to appear) <br>
https://arxiv.org/abs/2302.04955, 2023 <br>
<br>
10. M.F.P. ten Eikelder, K.G. van der Zee, I. Akkerman, D. Schillinger,<br>
A unified framework for Navier-Stokes Cahn-Hilliard models with non-matching densities, <br>
Mathematical Models and Methods in Applied Sciences 33, 175-221, 2023 <br>
<br>
9. M.F.P. ten Eikelder, I. Akkerman, <br>
A novel diffuse-interface model and a fully-discrete maximum-principle-preserving energy-stable method for two-phase flow with
surface tension and non-matching densities,<br>
Computer Methods Applied Mechanics and Engineering 379: 113751, 2021<br>
<br>
8. S.K.F. Stoter, M.F.P. ten Eikelder, F. de Prenter, I. Akkerman, E.H. van Brummelen, C.V. Verhoosel, D. Schillinger, <br>
Nitsche’s method as a variational multiscale formulation and a resulting boundary layer fine-scale model, <br>
Computer Methods Applied Mechanics and Engineering 382: 113878, 2021 <br>
<br>
7. I. Akkerman, J.H.A. Meijer, M.F.P. ten Eikelder, <br>
Isogeometric analysis of linear free-surface potential flow, <br>
Ocean Engineering 201: article 107114, 2020 <br>
<br>
6. M.F.P. ten Eikelder, Y. Bazilevs, I. Akkerman,<br>
A theoretical framework for discontinuity capturing: Joining variational multiscale analysis and variation entropy
theory,<br>
Computer Methods Applied and Mechanics Engineering 359: article 112664, 2020 <br>
<br>
5. M.F.P. ten Eikelder, I. Akkerman, <br>
Variation entropy: a continuous local generalization of the TVD property using entropy principles, <br>
Computer Methods Applied Mechanics and Engineering 355: 261-283, 2019 <br>
<br>
4. I. Akkerman, M.F.P. ten Eikelder,<br>
Toward free-surface flow simulations with correct energy evolution: an isogeometric level-set approach with monolithic time-integration,<br>
Computers and Fluids 181: 77-89, 2019 <br>
<br>
3. M.F.P. ten Eikelder, I. Akkerman,<br>
Correct energy evolution of stabilized formulations: The relation between VMS, SUPG and GLS via dynamic orthogonal small-scales and isogeometric analysis. II: The incompressible Navier-Stokes equations,<br>
Computer Methods Applied Mechanics and Engineering 340: 1135-1159, 2018 <br>
<br>
2. M.F.P. ten Eikelder, I. Akkerman, <br>
Correct energy evolution of stabilized formulations: The relation between VMS, SUPG and GLS via dynamic orthogonal small-scales and isogeometric analysis. I: The convective-diffusive context, <br>
Computer Methods Applied Mechanics and Engineering 331: 259-280, 2018 <br>
<br>
1. M.F.P. ten Eikelder, F. Daude, B. Koren, A.S. Tijsseling, <br>
An acoustic-convective splitting-based approach for the Kapila two-phase flow model, <br>
Journal of Computational Physics 331: 188-208, 2017 <br>
<br>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
