---
title: Block AMR Verification Tooling (Parthenon)
order: 4
role: >
  Developed over a year in collaboration with a senior researcher to build an independent Python-based verification codebase for adaptive mesh refinement (AMR) workflows.
outcome: >
  Created an independent validation framework used to reproduce and verify AMR blocking behavior across dimensionalities and refinement scales.
problem: >
  Adaptive mesh refinement (AMR) behavior in large simulation codes can be difficult to verify independently, especially when multiple dimensionalities, blocking configurations, and refinement rules must be respected. Existing tooling could only correctly handle a limited subset of 2D cases and did not scale well to larger configurations.
solution:
  - Implemented a separate Python codebase that replicated AMR blocking behavior independent of the original Parthenon implementation
  - Added support for both 2D and 3D mesh adaptation across a wide range of block sizes
  - Implemented rule-checking logic to enforce valid refinement constraints between neighboring blocks during iterative adaptation
  - Extended the system to automatically evaluate case validity and stop once no further valid mesh changes were possible
  - Improved performance and scalability to handle larger validation cases, including HPC-scale runs when necessary
impact:
  - Expanded verification coverage from a limited set of 2D cases to robust handling of most feasible blocking configurations in both 2D and 3D
  - Enabled independent validation against known reference solutions for multiple AMR scenarios
  - Provided a flexible testing tool to support exploration and evaluation of algorithmic changes
---
