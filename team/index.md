---
title: Team
nav:
    order: 3
    tooltip: About our team
redirect_from:
    - /lab-members
    - /alums
    - /mascots
    - /staff
    - /trainees
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: msc, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html dark=true %}

Prof. Dalmolin supervises in the post-graduate program in Bioinformatics at the Federal University of Rio Grande do Norte, which offers both Master and PhD courses. Come visit us or, better yet, join us!

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="https://sigaa.ufrn.br/sigaa/public/programa/apresentacao.jsf?lc=pt_BR&id=9814"
  style="button"
%}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: msc, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" %}

{% include section.html %}

{%
  include figure.html
  image="images/grupo_foto2.jpg"
  caption="Some of our team (plus a few friends!) at ICe"
  width="100%"
%}
