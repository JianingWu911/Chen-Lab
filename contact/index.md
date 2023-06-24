---
title: Contact
nav:
  order: 3
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab members come from the following institutions:
1. State Key Laboratory of Mechanical System and Vibration, Shanghai Jiao Tong University, Shanghai 200240, China.
2. School of Mechanical Engineering, Shanghai Jiao Tong University, Shanghai 200240, China.
3. Meta Robotics Institute, Shanghai Jiao Tong University, Shanghai 200240, China.

{%
  include button.html
  type="email"
  text="ffchen@sjtu.edu.cn"
  link="ffchen@sjtu.edu.cn"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/j5MvDPxDZj4XMWsc6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/sjtu.jpeg"
  caption="Shanghai Jiao Tong University"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/me1.jpg"
  caption="School of Mechanical Engineering, Shanghai Jiao Tong University"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/mate.jpg"
  caption="Meta Robotics Institute, Shanghai Jiao Tong University"
%}


{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3%}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}
