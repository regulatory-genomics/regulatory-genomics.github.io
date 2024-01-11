---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We're a team of scientists using computational and quantitative tools to advance our understanding of gene regulation in mammalian cells.
We believe that collaboration and community are crucial to advancing scientific research in this field.
We promote a culture of equality within our team, where each member is valued and our differences are recognized and celebrated with respect and admiration.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}
{% include list.html data="members" component="portrait" filters="role: ra" %}
{% include list.html data="members" component="portrait" filters="role: vs" %}

{% include section.html background="images/background.jpg" dark=true %}

We are always looking for individuals of all levels and backgrounds to join our team and contribute their unique talents and perspectives.
Join us today in our mission to uncover the secrets of gene regulation and make a difference in the world of regulatory genomics!

{% include button.html icon="fa-solid fa-users" text="Join the Team" link="join" style="button" %}


{% include section.html %}

# Alumni

{% include list.html data="alumni" component="portrait" filters="role: postdoc" %}
{% include list.html data="alumni" component="portrait" filters="role: phd" %}
{% include list.html data="alumni" component="portrait" filters="role: undergrad" %}
{% include list.html data="alumni" component="portrait" filters="role: ra" %}
{% include list.html data="alumni" component="portrait" filters="role: vs" style="small" %}