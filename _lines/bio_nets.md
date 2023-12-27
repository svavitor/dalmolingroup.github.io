---
title: Analysis of biological networks
subtitle: "Regulatory networks, PPI and coexpression"
image: images/lines/networks.png
link: lines/bio_nets
---

Biological Network Analysis is a dynamic and interdisciplinary field that allows the integration and interpretation of complex biological information through the analysis of interactions among biological entities, be they genes, proteins, metabolites, or other molecules.
This approach has enabled the identification of key biological components, regulatory mechanisms and functional modules involved in biological pathways and diseases.

The Dalmolin Group has been using biological network analysis to uncover biological mechanisms since 2008.
The first work was an integration between Protein-Protein Interactions network and orthology, resulting in an orthology map in order to locate the eukaryotic genes in the human apoptosis and genome-stability gene/protein-association network ([Castro et al, 2008](https://doi.org/10.1093/nar/gkn636)).
Subsequently, this approach was used to model gene networks based on transcriptional data that responds selectively to both hypoxia and acidosis ([Dalmolin et al, 2012](https://doi.org/10.2741/S352)).

Over the last decade, the group has been exploring a tool that builds networks based on regulatory units ([The RTN package](https://bioconductor.org/packages/release/bioc/html/RTN.html)) with the aim of modeling transcriptional networks and identifying master regulators associated with the investigated phenotypes.
This method has helped us understand the global regulome and identify regulators responsible for triggering several diseases, including Ewing Sarcoma ([Ribeiro-Dantas et al, 2021](https://doi.org/10.3390/cancers13081860)), Neuroblastoma ([Albanus et al, 2013](https://doi.org/10.1371/journal.pone.0082457)), Pediatric Sepsis ([Oliveira et al, 2021](https://doi.org/10.3390/biomedicines9101297)), and metastatic prostate cancer ([Ferraz et al, 2023](https://doi.org/10.1002/cam4.6481)).
Our perspective for the coming years is to explore the regulatory network at the cellular level, investigating the gene interactions that occur cell to cell.

{%
  include figure.html
  caption="From Ribeiro-Dantas et al, 2021. Regulatory map (TF-centric regulatory network) of the seven common master regulators in network 1 (GSE34620). Gray squares are transcription factors (TFs) that are here inferred as mater regulators (MRs) and circles are genes regulated by at least one of the seven MRs. The edges indicate regulation and the color of the edge indicates the type of regulation (red for positive regulation, activation, and blue for negative regulation, inhibition). The circles follow the same color scheme, except that whenever a gene is positively regulated by one TF and negatively regulated by another TF, it is colored gray."
  image="images/lines/networks.png"
%}
