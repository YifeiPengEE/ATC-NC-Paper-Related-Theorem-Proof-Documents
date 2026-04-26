# ATC-NC-Paper-Related-Theorem-Proof-Documents
# Overview

## Main Paper

`globecom_paper_en.tex` presents TAC-NC, a unified Network Calculus framework for worst-case delay analysis in Time-Sensitive Networking (TSN) with combined shapers. The paper addresses three main limitations of existing methods: loose arrival-curve modeling, reliance on manually derived service curves, and the difficulty of handling cyclic topologies. To overcome these issues, TAC-NC integrates BOM-based arrival-curve tightening with packet-level discretization, WOM-based automated service-curve construction, and a fixed-point method for cyclic analysis. Both the theoretical results and the experiments show that TAC-NC can generate sound Network Calculus curves, support cyclic TSN analysis, and improve modeling efficiency, tightness, and schedulability.

## Supplementary Material

`atc_nc_supplementary_readable_en.tex` is the supplementary material for `globecom_paper_en.tex`. It provides the detailed derivations and formal proofs of the key theorems stated in the main paper, especially those concerning the validity of the constructed arrival and service curves, the convergence of the fixed-point iteration, and the safety of the resulting worst-case delay bounds.
