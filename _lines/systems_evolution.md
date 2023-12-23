---
title: Evolution of biological systems
description: Systemic root inference of orthologous groups
---

# An algorithm to systemically infer the evolutionary root of orthologous groups

The development of sequencing technologies in the past two decades allowed the study of the phylogenetic relationship of several model organisms. An interesting question relies on the mechanisms behind how new genes arise and how they interact and evolve together to build the intricate network of genes observed in the organism's biochemical pathways. A strategy is proposed in [Castro et al, 2008](https://doi.org/10.1093/nar/gkn636) and in [Dalmolin et al, 2011](https://biologydirect.biomedcentral.com/articles/10.1186/1745-6150-6-22) papers, and it envolves two main steps. First, a consensus phylogeny for eukaryotes is constructed. The second step involves reconstructing the evolutionary scenario for each set of orthologous genes. This step aims to find the most parsimonious mapping of orthologs on the species tree, determining the earliest ortholog for each orthologous group associated with a given gene. The algorithm is implemented as an R/Bioconductor package called [geneplast](https://www.bioconductor.org/packages/release/bioc/html/geneplast.html).

{%
  include figure.html
  caption="From the geneplast vignette, we show the evolutionary rooting scenarios . Red circles indicate the evolutionary roots that best explain the observed orthologs in the species tree."
  image="images/lines/evo1.png"
%}

# This approach was used to unravel the evolution of biochemical systems, such as... 

## Human apoptosis and genome-stability 

In the [Castro et al., 2008](https://doi.org/10.1093/nar/gkn636), we estimated the evolutionary root for the apoptosis and the genome-stability genes and we found that many cancer genes are located in the earlier, more plastic and less essential region. 

{%
  include figure.html
  caption="From Castro et al., 2008. Human apoptosis and genome-stability gene network."
  image="images/lines/evo5.jpeg"
%}

## Human synapses

In the [Viscardi et al. 2020](https://doi.org/10.1093/molbev/msaa252) paper, we aimed to reconstruct the evolutionary history of the human neurotransmission gene network by analyzing genes in major neurotransmitter systems. The findings suggest that the emergence of receptor families, particularly ionotropic receptors, at the Human–Cnidaria Last Common Ancestor played a crucial role in the evolution of synapses, even before their establishment in Ctenophores.

{%
  include figure.html
  caption="From Viscardi et al, 2020. Human neurotransmission protein-protein interaction network. Nodes represent proteins, whereas edges represent the interactions among them. Node size is proportional to the number of neuronal pathways it participates (i.e., GABAergic, cholinergic, serotonergic, glutamatergic, and dopaminergic). The UpSet diagram depicts how nodes are distributed among pathways (e.g., 31 genes take part in all five pathways)."
  image="images/lines/evo2.jpeg"
%}

## The reactive oxygen species system in *Arabidopsis thaliana*

In the [Oliveira et a., 2019](https://www.nature.com/articles/s41598-019-52299-y) paper, we used orthologous groups information from 238 eukaryotes to perform an evolutionary analysis of genes related to reactive oxygen species (ROS) in *Arabidopsis thaliana*. We found two interconnected clusters of ROS genes: one formed by SOD-related, Thiol-redox, peroxidases, and other oxido-reductase; and the other formed entirely by class III peroxidases. Each cluster emerged in different periods of evolution: the cluster formed by SOD-related, Thiol-redox, peroxidases, and other oxido-reductase emerged before opisthokonta-plant divergence; the cluster composed by class III peroxidases emerged after opisthokonta-plant divergence and therefore contained the most recent network components. According to our results, class III peroxidases are in expansion throughout plant evolution, with new orthologs emerging in each evaluated plant clade divergence.

{%
  include figure.html
  caption="From Oliveira et al., 2019. *Arabidopsis thaliana* redox protein-protein interaction network."
  image="images/lines/evo4.jpg"
%}

## Essential genes in eukaryotes

In [De Souza et al, 2021](https://doi.org/10.1007/s10142-021-00794-9) paper, essential genes from five model eukaryotes were analyzed to determine if they differ in age from non-essential genes. The study compared network properties and investigated the biological functions of essential genes in each species, revealing that essential genes are rooted in different evolutionary periods. Despite varying origins, essential genes tend to be older and more connected than other genes across all evaluated model species.

{%
  include figure.html
  caption="From De Souza, 2021. Ancestry distribution of essential and other genes. Values tending to 1 indicate the oldest genes and values tending to 0 indicate the youngest genes. Black dot is the mean ancestry value for each ancestry distribution. Wilcoxon test, ****p-value < 0.0001."
  image="images/lines/evo3.jpg"
%}
