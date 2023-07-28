---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

## Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

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
{%
  include button.html
  type="address"
  text="Memorial Sloan Kettering Cancer Center"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/yc3mL38ZkpeqSZQ39"
%}

{%
  include button.html
  type="work"
  text="Open Positions"
  link="https://www.mskcc.org/research-areas/labs/elli-papaemmanuil/jobs"
%}

{% include section.html %}

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
  image="images/lab-edge.jpg"
  caption="We are strongly committed to mentoring young scientists through internal and international internship schemes"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

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

<a class="twitter-timeline" href="https://twitter.com/PapaemmanuilLab?ref_src=twsrc%5Etfw">Tweets by PapaemmanuilLab</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>