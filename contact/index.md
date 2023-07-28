---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

## Contact

{% capture col1 %}

{%
  include figure.html
  image="https://lirp.cdn-website.com/1b7412be/dms3rep/multi/opt/MSKCC_2-dfeddf4b-640w.jpg"
  caption="Our group is located at Joy/Maclowe building 321 E 61sth, at Memorial Sloan Kettering Cancer Center in New York City."
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/emerging-leaders-2023.jpeg"
  caption="We are strongly committed to mentoring young scientists through internal and international internship schemes"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col1 %}
{%
  include button.html
  type="email"
  text="papaemme@mskcc.org"
  link="papaemme@mskcc.org"
%}
{%
  include button.html
  type="phone"
  text="646-608-7645"
  link="+1 646-608-7645"
%}
{% endcapture %}

{% capture col2 %}
{%
  include button.html
  type="address"
  text="Memorial Sloan Kettering"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/yc3mL38ZkpeqSZQ39"
%}
{%
  include button.html
  type="work"
  text="Open Positions"
  link="https://www.mskcc.org/research-areas/labs/elli-papaemmanuil/jobs"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

###  Follow us on social media:

<a class="twitter-timeline" href="https://twitter.com/PapaemmanuilLab?ref_src=twsrc%5Etfw">Tweets by PapaemmanuilLab</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>