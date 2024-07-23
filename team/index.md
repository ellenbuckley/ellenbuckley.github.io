---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Dr. Buckley started the Buckley Lab at the University of Illinois in Fall 2024. We are looking for more members! If you are an undergrad at U of I looking for research experience, prospective graduate student or postdoc, please visit the "Contact" tab to get in touch.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.-->

{% include section.html %}

<!--{% capture content %}

{% include figure.html image="images/marvin" %}
{% include figure.html image="images/marvin" %}
{% include figure.html image="images/marvin" %}

{% endcapture %}-->

{% include grid.html style="square" content=content %}
