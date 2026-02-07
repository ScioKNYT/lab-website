---
title: Team
nav:
  order: 2
  tooltip: About our team and mission
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the researchers behind the SMART Lab.

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' or role == 'pi'" %}

## Current Members

{% include list.html data="members" component="portrait" filter="group != 'alumni' and role != 'pi' and role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Alumni

{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}

{% include section.html %}

{% capture content %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}

{% include grid.html style="square" content=content %}
