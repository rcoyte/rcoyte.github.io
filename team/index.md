---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="tier: first" %}
{% include list.html data="members" component="portrait" filters="tier: second" %}
{% include list.html data="members" component="portrait" filters="tier: " %}

{% include section.html dark=true %}

Whether you are a scientist looking to step into an emerging field with your data, an organization interested in investing in this work, or if you are simply curious and would like to stay informed about how translational science will evolve, we welcome your partnership. We work with leading scientists around the world and are funded by large national grants and institutions with new discoveries emerging every day.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% comment %}



