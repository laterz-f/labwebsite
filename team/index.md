---
title: People
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our lab is the Genomics of the Immune System Unit, which belongs to the San Raffaele Telethon Institute for Gene Therapy (SR-Tiget).

{% include section.html %}

# <i class="fas fa-users"></i>Principal investigator
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{:.center}


{% include section.html %}
# <i class="fas fa-users"></i>Lab members
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: wet lab"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: computational"
%}
{:.center}

{% include section.html %}

# <i class="fas fa-users"></i>Alumni

{% include section.html %}

## Join us!

We are constantly looking for energetic and enthusiastic individuals at all career stages. Unsolicited applications are always welcome!

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
