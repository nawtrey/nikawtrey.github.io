---
title: Kinetic Diagram Analysis Python Library
order: 2
role: >
  Developed in close collaboration with a principal investigator as a long-term research software project, resulting in an open-source scientific Python package.
outcome: >
  Transformed a mathematically intensive manual workflow into a reusable Python library that programmatically generates exact steady-state expressions for kinetic models with minimal computational overhead.
problem: >
  Steady-state analysis of biochemical kinetic networks is commonly performed using numerical approximations, while exact diagram-based methods (King–Altman / Hill) become impractical by hand as model complexity grows. The number of required intermediate diagrams increases factorially with system size, making manual derivation infeasible even for moderately sized models.
solution:
  - Developed a Python package that programmatically generates kinetic diagrams and symbolic algebraic expressions from user-defined models
  - Automated construction of steady-state probabilities and cycle flux expressions based on diagrammatic methods
  - Designed the library to integrate easily into existing computational workflows and symbolic analysis pipelines
  - Implemented symbolic workflows that allow expressions to be manipulated and evaluated programmatically
impact:
  - Enabled exact steady-state analyses as an alternative to approximation-based numerical methods
  - Converted a factorial-growth manual derivation process into an automated computational workflow
  - Produced symbolic outputs that can be reused across multiple analytical and modeling pipelines
  - Released as open-source software and published in JCTC
links:
  - label: Journal Publication (JCTC)
    url: https://pubs.acs.org/doi/10.1021/acs.jctc.4c00688
  - label: Project Repository
    url: https://github.com/Becksteinlab/kda
---
