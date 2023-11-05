---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

#### Alumni

{% include list.html data="members" component="portrait" filters="status: alumni" %}

{% capture content %}

Our lab is growing and actively recruiting new students! Please see the link below for more information. 

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}

{% endcapture %}

{% include grid.html style="square" content=content %}




