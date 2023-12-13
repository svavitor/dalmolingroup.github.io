---
title: Contact
nav:
    order: 5
    tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Federal University of Rio Grande do Norte’s [Bioinformatics Multidisciplinary Environment](https://bioinfo.imd.ufrn.br/site). Our team is headquartered on the 2nd Floor of the [Brain Institute](https://neuro.ufrn.br/) (ICe).

{% include figure.html image="images/biome_logo_atual.png" link="https://bioinfo.imd.ufrn.br/site" width="500px" %}

{%
  include button.html
  type="email"
  text="rodrigo.dalmolin@imd.ufrn.br"
  link="rodrigo.dalmolin@imd.ufrn.br"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/EwQLm7f39YF5e8kw8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/ice_foto.jpg"
  caption="© Cícero Oliveira"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/ice_foto2.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
