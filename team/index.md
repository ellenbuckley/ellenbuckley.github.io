---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Dr. Ellen Buckley started at the University of Illinois in the Fall of 2024 and is looking to expand the group! If you are an undergrad at UIUC looking for research experience, or a prospective graduate student or postdoc, please visit the "Contact" tab to get in touch.

{% include section.html %}



{% include list.html data="members" component="portrait"  sort_by="order" sort_order="ascending" %}

{% include section.html background="images/background.jpg" dark=true %}



{% include section.html %}

{% capture content %}

<!-- {% include figure.html image="images/marvin" %}-->
<!-- {% include figure.html image="images/marvin" %}-->
<!-- {% include figure.html image="images/marvin" %}-->

{% endcapture %}

{% include grid.html style="square" content=content %}
