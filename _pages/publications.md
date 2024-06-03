---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<div class="wordwrap">
My research has two primary objectives. Firstly, I aim to generate work that holds significance both academically and in practical business contexts. Secondly, I strive to produce research that is accessible and comprehensible even to non-specialists.

I am currently focusing my research on the domains of non-fungible tokens and dating. My papers have been invited for presentation at various premier venues and have received nominations for best paper (ICIS 2023) and best student paper (WISE 2022). My research pipeline includes further exploration of non-fungible tokens and dating, as well as expansion into the realms of online streaming and real estate. 

I primarily acquire data for my research through methods such as web scraping and accessing APIs. Additionally, in some cases, I am also incorporating experimental research methods and collaborating with companies.
</div>

{% for post in site.publications %}
  {% include my-archive-single.html %}
{% endfor %}
