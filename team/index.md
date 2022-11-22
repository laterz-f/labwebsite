---
title: People
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Meet the members of the Genomics of the Immune System Unit! 
Our lab is part of the San Raffaele Telethon Institute for Gene Therapy (SR-Tiget).

{% include section.html %}

# Principal investigator
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{:.center}


{% include section.html %}
# Current Lab members
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc wet"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc computational"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: assistant wet"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd wet"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd computational"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad wet"
%}
{:.center}

{% include section.html %}

# Alumni

<br>

| Alumni | Role | Now |
| :------------- |:-------------| :-----------|
| Elisa Montaldo    | Postdoctoral Researcher  | Staff scientist at SR-Tiget Process Development Lab |
| Eleonora Lusito    | Postdoctoral Researcher | ... |
| Francesco Cilenti	   | PhD Student | ... |
| Mattia Barilaro | Research fellow | ... |
| Dario Iodice | Research Fellow | ... |
| Valentina Bianchessi | PhD Student | ... |
| Carla Cantaffa | ... | ... |

{% include section.html 
   background="images/background.jpg"
   dark=true
   full=false
 %}

## Join us!

We are constantly looking for energetic and enthusiastic individuals at all career stages. 
Unsolicited applications are always welcome!

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/erc.png"
  link1="https://erc.europa.eu/homepage"
  tooltip1="ERC"

  image2="images/airc.jpg"
  link2="https://www.airc.it/"
  tooltip2="AIRC Foundation"

  image3="images/telethon.png"
  link3="https://www.telethon.it/"
  tooltip3="Telethon Foundation"

  image4="images/mur.png"
  link4="https://www.salute.gov.it/portale/home.html/"
  tooltip4="Italian Ministry of Health"

%}
