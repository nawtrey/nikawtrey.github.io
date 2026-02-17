---
title: Modernizing Darshan HPC Report Generation (PyDarshan)
order: 1
role: >
  Primary Python contributor working with a senior developer on a cross-lab effort to modernize the Darshan report summary tool within the PyDarshan ecosystem.
problem: >
  Darshan Runtime generates log files used to analyze I/O behavior on HPC systems. For years, users relied on a Perl-based report generator that produced static PDF summaries from these logs. While the workflow was widely adopted and useful, the codebase had become difficult to maintain and extend, limiting future development and making iterative improvements impractical.
solution:
  - Helped redesign and implement a modern report-generation system within the PyDarshan Python package, replacing the legacy Perl workflow
  - Implemented the majority of the report-building pipeline, generating modular HTML reports with embedded figures
  - Added new analyses and visualizations, including a primary heatmap analysis and additional figures driven by user feedback
  - Preserved existing analytical functionality while introducing a modular architecture that allows users to add custom analysis classes
  - Improved report generation performance relative to the original implementation
impact:
  - Modernized a widely used HPC reporting workflow while maintaining compatibility with established user expectations
  - Delivered portable HTML reports that were easier to share and view across environments compared to static PDFs
  - Expanded analytical capabilities while reducing report generation time
  - Created a more maintainable and extensible Python-based architecture supporting iterative development
  - Delivered a maintainable Python-based architecture intended to support iterative future development
links:
  - label: ACM Publication
    url: https://dl.acm.org/doi/abs/10.1145/3624062.3624207
  - label: Conference Slide Deck (Report Examples)
    url: https://per3s.github.io/material/2024_per3s_jakob_Luettgau.pdf
  - label: Darshan Project Homepage
    url: https://www.mcs.anl.gov/research/projects/darshan/
  - label: PyDarshan Source (GitHub)
    url: https://github.com/darshan-hpc/darshan/tree/main/darshan-util/pydarshan
---
