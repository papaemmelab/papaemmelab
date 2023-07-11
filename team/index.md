---
title: Team
nav:
  order: 3
  tooltip: About our team
---

## Team

Our lab is a collective of clinical, computational, molecular and mathematic research investigators. We like to perform ambitious research, but operate in a fun, collaborative, and team-oriented environment, and we are strongly committed to mentoring young scientists through internal and international internship schemes.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include list.html data="members" component="portrait" filters="status: active" %}

{% include section.html background="images/lab.jpg" dark=true %}

{% include section.html %}

#### Alumni

{% include list.html data="members" component="portrait" filters="status: alumni" %}

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
