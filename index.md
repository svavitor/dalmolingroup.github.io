---
---

# Where data and biology meet

Professor Dalmolin's systems biology research group advances biomedical knowledge through bioinformatics. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{% include figure.html image="images/group_foto.jpg" width="80%" %}

{% include section.html %}

## Highlights

{% capture text %}

Our research focuses on the Evolution of biological systems, Analysis of biological networks, Transcriptional and Metagenomic analyses and the Development of novel bioinformatics tools.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/our_research.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Streamline your investigation with our tools and pipelines. All open source and well documented.

{%
  include button.html
  link="tools"
  text="Browse our tools"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/tools/kpv_figure.jpg"
  link="projects"
  title="Tools by researchers, for researchers"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a team of interdisciplinary researchers working in the various fields of bioinformatics. We strive for excellence in research and diversity and inclusivity are our values.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/grupo_foto2.jpg"
  link="team"
  title="Building excellence in bioinformatics"
  text=text
%}

{% include section.html %}

## Our lines of research

{%
  include card.html
  image="images/lines/evolution.png"
  link="lines/systems_evolution.html"
  title="Evolution of biological systems"
  subtitle="A cool description"
  style="large"
%}

{%
  include card.html
  image="images/lines/networks.png"
  link="lines/bio_nets.html"
  title="Analysis of biological networks"
  subtitle="Regulatory networks, PPI and coexpression"
  style="large"
%}

{%
  include card.html
  image="images/lines/transcriptomics_line.jpg"
  link="lines/transcriptomics.html"
  title="Transcriptional analyses"
  subtitle="Microarray, Bulk RNA-seq and scRNA-seq"
  style="large"
%}

{%
  include card.html
  image="images/lines/metagenomics_lines.jpg"
  link="lines/metagenomics.html"
  title="Metagenomics analyses"
  subtitle="Diversity analysis, functional annotation and MAGs"
  style="large"
%}

{%
  include card.html
  image="images/lines/dev.png"
  link="lines/tools.html"
  title="Development of bioinformatics tools"
  subtitle="Pipelines, R packages and Python libraries"
  style="large"
%}
