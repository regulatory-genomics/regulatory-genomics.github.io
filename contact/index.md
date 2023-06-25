---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab locates at the Yunqi campus of Westlake University:

Westlake Laboratory 3#410, Shilongshan ST #18, Xihu District, Hangzhou, Zhejiang Province, China    
中国浙江省杭州市西湖区云栖小镇石龙山街18号, 西湖实验室, 3号楼410

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
  tooltip="Our location for easy navigation"
  link="https://map.baidu.com/poi/%E8%A5%BF%E6%B9%96%E5%AE%9E%E9%AA%8C%E5%AE%A4/@13368202.124999996,3499936.000000002,19z?uid=2c388130d2883a94fea778d0&info_merge=1&isBizPoi=false&ugc_type=3&ugc_ver=1&device_ratio=2&compat=1&pcevaname=pc4.1&querytype=detailConInfo&da_src=shareurl"
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
