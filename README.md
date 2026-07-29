 <div align="center">

<h1>Constraint-First Graph Pruning for Enterprise Knowledge Base Deduplication</h1>
<p>Jamal Kawach, Maryam Ebrahimi, Erin Li</p>

</div>

> This repository contains the implementation and materials of our paper, "Constraint-First Graph Pruning for Enterprise Knowledge Base Deduplication," submitted to the 35th ACM International Conference on Information and Knowledge Management (CIKM) 2026, Applied Research track.

## Abstract

Enterprise knowledge bases (KBs) in regulated industries often accumulate near-duplicate pages, inflating index size, increasing maintenance overhead, and introducing compliance risk. Standard deduplication methods lack hard guarantees for preserving compliance-critical content. We formalize *constraint-aware KB selection* as a seeded dominating set problem on a semantic similarity graph, with a business-rule-defined safeguard set that must be strictly retained, and introduce *Constraint-First Graph Pruning* (CFGP): a two-stage framework decoupling redundancy clustering (recall stage) from within-cluster pruning (precision stage, with optional Jaccard blending). Applied to a proprietary KB of 19,433 documents and 2,119 SME-verified query–document pairs, CFGP reduces index size by up to ~21%, improves key knowledge base health metrics, and guarantees zero loss of compliance-critical documents, all without degrading retrieval performance. The framework is currently under operational evaluation at a banking enterprise, where it is actively supporting large-scale content curation and is expected to substantially reduce manual effort in duplication detection and content retirement.

## Code Availability

Code and reproducibility artifacts are coming soon.

## License

A license will be provided with the code release.