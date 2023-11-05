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

{% include section.html %}

Our lab is growing and actively recruting new graduate students!
{%
  include button.html
  type="lab address"
  text="Join Us"
  link="join"
%}
