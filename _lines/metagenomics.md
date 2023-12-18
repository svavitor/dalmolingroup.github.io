---
title: Metagenomics analyses
description: Diversity analysis, functional annotation and MAGs
---

# Where do we start?

Metagenomics data, or data containing the full genetic content of an environmental sample, constitutes one of our current research topics at the Dalmolin Group. Metagenomics data provides a great potential for studying the diversity and functional activity of complex microbial environments.

Our studies of metagenomics data began with the development of our in-house pipeline for processing these data, [MEDUSA](https://github.com/dalmolingroup/medusa) ([Morais et al, 2022](https://doi.org/10.3389/fgene.2022.814437)). With MEDUSA, we aimed to build a sensitive, flexible and reproducible pipeline that produces taxonomic classification and functional annotation of metagenomics reads. Below, you can see a diagram detailing the different steps of the original MEDUSA pipeline. We later reimplemented MEDUSA in another workflow orchestration language, Nextflow, this time being called [EURYALE](https://github.com/dalmolingroup/euryale).

{%
  include figure.html
  caption="From Morais et al, 2022. The MEDUSA analysis workflow. Squares highlight the protocol steps, and third-party tools are depicted as cyan capsules. The python icon represents the tool implemented for the functional annotation."
  image="images/lines/metagenomics_1.jpg"
%}

# Current work and future directions

Some of our work exploring metagenomics data is highlighted by "Metagenomic Analyses Reveal the Influence of Depth Layers on Marine Biodiversity on Tropical and Subtropical Regions" ([Santiago et al, 2023](https://doi.org/10.3390/microorganisms11071668)). In this work, using MEDUSA, we observed differences in diversity between three ocean layers in the Tropical and Subtropical regions and also noted different functional annotations between these layers.

And now, with MEDUSA/EURYALE and all of the software in the metagenomics ecosystem, we aim to keep exploring metagenomics data, with a focus on functional analysis.

{%
  include figure.html
  caption="From Santiago et al, 2023. Diversity and abundance distribution by depth layer in the tropical and subtropical regions."
  image="images/lines/metagenomics_2.jpg"
%}
