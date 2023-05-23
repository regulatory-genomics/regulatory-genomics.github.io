---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab locates at the Yunqi campus of Westlake University.

{%
  include button.html
  type="email"
  text="zhangkai33@westlake.edu.cn"
  link="zhangkai33@westlake.edu.cn"
%}
{%
  include button.html
  type="phone"
  text="(858) 900-6852"
  link="+1-858-900-6852"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/westlake_university1.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/westlake_university2.png"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% comment %}

{% include section.html dark=true %}

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

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% endcomment %}
