---
title: Home
---

# Welcome to Ostuni lab!

We are a <b>multidisciplinary group</b> that combines <b>high-throughput and single-cell genomics</b>, <b>bioinformatics</b>, <b>genome engineering</b> and <b>functional studies</b> to dissect principles of immune cell development and functions. Building on relevant mouse models and uniquely available clinical samples, we aim to decipher the complex networks of signaling pathways, transcription factors, chromatin regulators and non-coding RNAs that control <b>gene expression in the innate immune system</b>.

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Over the years, we have revealed molecular circuits and regulatory strategies underlying innate immune cell activity. These discoveries have profound implications for cancer immunotherapy and tissue regeneration.
{%
  include link.html
  link="research"
  text="See what we do"
  icon="fas fa-arrow-right"
  flip=true
%}
{%
  include link.html
  link="publications"
  text="Check out our publications"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research-home.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/tools.png"
  link="tools"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
Our team is made up by people with diverse background and skills. We work in synergy to do great science (and have fun!).

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/lab_home.jpg"
  link="team"
  title="Our Team"
  text=text
%}
