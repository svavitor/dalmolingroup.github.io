---
title: Evolution of biological systems
description: Systemic root inference of orthologous groups
---

# An algorithm to infer the evolutionary root of orthologous groups

The development of sequencing technologies in the past two decades allowed the study of the phylogenetic relationship of several model organisms. An interesting question relies on the mechanisms behind how new genes arise and how they interact and evolve together to build the intricate network of genes observed in the organism's biochemical pathways. Gene duplication is highlighted as a crucial event in genome evolution, offering a prime source for genetic material and allowing evolutionary forces to generate novelty. In the [Dalmolin et al, 2011](https://biologydirect.biomedcentral.com/articles/10.1186/1745-6150-6-22) paper, the importance of duplication events in the evolutionary history of orthologous groups is assessed by the ratio of components to the number of organisms with items from the group. The study extends to analyze Eukaryotic Clusters of Orthologous Groups (KOG) in STRING, evaluating the evolutionary plasticity and conservation of groups based on component distribution across eukaryotic genomes, proposing an equation for plasticity, and identifying correlations between evolutionary distance and plasticity. The algorithm used in this paper to infer the evolutionary root of orthologous groups, based on a phylogenetic tree from eukaryotes, is implemented as an R/Bioconductor package called [geneplast](https://www.bioconductor.org/packages/release/bioc/html/geneplast.html).

{%
  include figure.html
  caption="From the geneplast vignette, we show the evolutionary rooting scenarios . Red circles indicate the evolutionary roots that best explain the observed orthologs in the species tree."
  image="images/lines/evo1.png"
%}

# This approach was used to unravel the evolution of biochemical systems, such as human synapses

In the [Viscardi et al. 2020](https://doi.org/10.1093/molbev/msaa252) paper, we aimed to reconstruct the evolutionary history of the human neurotransmission gene network by analyzing genes in major neurotransmitter systems. The findings suggest that the emergence of receptor families, particularly ionotropic receptors, at the Human–Cnidaria Last Common Ancestor played a crucial role in the evolution of synapses, even before their establishment in Ctenophores.

{%
  include figure.html
  caption="From Viscardi et al, 2020. Human neurotransmission protein-protein interaction network. Nodes represent proteins, whereas edges represent the interactions among them. Node size is proportional to the number of neuronal pathways it participates (i.e., GABAergic, cholinergic, serotonergic, glutamatergic, and dopaminergic). The UpSet diagram depicts how nodes are distributed among pathways (e.g., 31 genes take part in all five pathways)."
  image="images/lines/evo2.jpeg"
%}

# And essential genes

In [De Souza et al, 2021](https://doi.org/10.1007/s10142-021-00794-9) paper, essential genes from five model eukaryotes were analyzed to determine if they differ in age from non-essential genes. The study compared network properties and investigated the biological functions of essential genes in each species, revealing that essential genes are rooted in different evolutionary periods. Despite varying origins, essential genes tend to be older and more connected than other genes across all evaluated model species.

{%
  include figure.html
  caption="From De Souza, 2021. Ancestry distribution of essential and other genes. Values tending to 1 indicate the oldest genes and values tending to 0 indicate the youngest genes. Black dot is the mean ancestry value for each ancestry distribution. Wilcoxon test, ****p-value < 0.0001."
  image="images/lines/evo3.jpg"
%}
