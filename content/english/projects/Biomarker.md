---
title: Biomarker Discovery
date: 2025-06-01
image: "/images/biomarker.png"
description: this is meta description
tags: ["Biomarker"]
categories: []
author: "Jie Wu"
---

One of my major responsibilities at Accent was to identify candidate predictive biomarkers for its oncology drugs. Since I joined Accent, I developed a biomarker discovery platform capable of handling various tasks to identify and explore potential biomarkers. The platform consists of an Accent proprietary database and a set of code that can efficiently generate biomarker reports with compound response data.

The platform can do the following semi-automatic analysis:

Data input:

-   IC50s/EC50s/AUCs for response-based analysis
-   Sensitivity class for two class analysis
-   Genomics data curated from CCLE/sanger/CROs

Routine biomarker discovery analysis at Accent:

-   Damaging mutation enrichment (Fisher or Wilcoxon test)
-   Copy number enrichment (limma::lmfit or Wilcoxon test)
-   Gene expression (limma::lmfit or spearman correlation)
-   Chronos and Demeter2 Scores (correlation)
-   GDSC and PRISM response (correlation)
-   Global markers, e.g. MSI, Aneuploidy, Whole genome Doubling, TMB (correlation or Wilcoxon)
-   Feature ranking and selection (Random Forest, PLS-DA/PLS)
-   Other (methylation, chromatin status, protein expression)

Output

-   Interactive HTML report (Rmarkdown)

