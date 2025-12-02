---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<p align="justify"> I have two primary research objectives. First, I aim to generate work that holds significance both in academic and in practical business contexts. Second, I strive to produce research that is accessible and comprehensible to a broader audience, including those outside the field. <br /></p>

<p align="justify"> I am currently focusing my research on the domains of non-fungible tokens and dating. My papers have been invited for presentation at various premier venues and have received nominations for best paper (ICIS 2023) and best student paper (WISE 2022). My research pipeline includes further exploration of non-fungible tokens and dating, as well as expansion into the realms of artificial intelligence, online streaming, and real estate.<br /></p>

<p align="justify"> I primarily acquire data for my research through methods such as web scraping and accessing APIs. Additionally, in some cases, I am also incorporating experimental research methods and collaborating with companies.<br /></p>

<hr>

<b><u>Journal Publications</u></b>

{% for post in site.publications %}
  {% if post.published == "yes" %}
    {% include my-archive-single.html %}
  {% endif %}
{% endfor %}

<hr>

<b><u>Work in Progresss</u></b>

{% for post in site.publications %}
  {% if post.published == "no" %}
    {% include my-archive-single.html %}
  {% endif %}
{% endfor %}