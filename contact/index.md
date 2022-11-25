---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [San Raffaele Telethon Institute for Gene Therapy](https://research.hsr.it/en/institutes/san-raffaele-telethon-institute-for-gene-therapy.html), at [San Raffaele Hospital](https://www.hsr.it/) in Milan.\
We are located on the 1st floor of Dibit1.
{:.center}

{%
  include link.html
  type="email"
  icon=""
  text="Send us an email"
  tooltip=""
  link="ostuni.renato@hsr.it"
  style="button"
%}

{%
  include link.html
  type="address"
  icon=""
  text="Find us on Google Maps"
  tooltip="Our location on Google Maps"
  link="https://www.google.com/maps/place/DiBiT+1/@45.5276938,9.4278141,14.05z/data=!4m5!3m4!1s0x0:0x8bc9ddd65df565e6!8m2!3d45.5068049!4d9.2669577"
  style="button"
%}
{:.center}

{% include section.html %}

{% capture col1 %}
{%
  include figure.html
  image="images/sr-tiget.jpg"
  caption="San Raffaele Telethon Institute for Gene Therapy"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/hsr.jpg"
  caption="San Raffaele Hospital"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
