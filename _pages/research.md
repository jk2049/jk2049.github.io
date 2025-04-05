---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<p align="justify"> Abstract: My research has two primary objectives. Firstly, I aim to generate work that holds significance both academically and in practical business contexts. Secondly, I strive to produce research that is accessible and comprehensible even to non-specialists.<br /></p>

<p align="justify"> Abstract: I am currently focusing my research on the domains of non-fungible tokens and dating. My papers have been invited for presentation at various premier venues and have received nominations for best paper (ICIS 2023) and best student paper (WISE 2022). My research pipeline includes further exploration of non-fungible tokens and dating, as well as expansion into the realms of online streaming and real estate.<br /></p>

<p align="justify"> I primarily acquire data for my research through methods such as web scraping and accessing APIs. Additionally, in some cases, I am also incorporating experimental research methods and collaborating with companies.<br /></p>

<hr>

{% for post in site.publications %}
  {% include my-archive-single.html %}
{% endfor %}
