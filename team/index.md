---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of a highly engaged and collaborative team of researchers. We recognize that diverse teams do better research. We foster an environment where team members are treated equally, and where we respect and admire our differences. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: m.s." %}

{% include section.html background="images/background2.jpeg" dark=true %}


{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="alumni" component="portrait" filters="role: m.s." %}
{% capture content %}


{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
