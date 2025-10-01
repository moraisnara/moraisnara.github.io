---
layout: archive
title: "Reseach"
permalink: /publications/
author_profile: true
---

The Role of Local Politicians on Environmental Degradation: Evidence
from Brazil (with Bruno Miranda) 

Presented at: _ENABER 2024, ANPEC 2024, Microeconomic LAERE 2025_

This paper investigates the role of local political leadership in shaping environmental outcomes in Brazil. Specifically, we examine whether the election of left-wing mayors—who are typically more aligned with pro-environmental agendas—leads to lower levels of environmental degradation. Combining electoral with environmental data, we find that electing a left-wing mayor reduces deforestation by 34 km², nearly 8\% of the control mean. These effects are robust across specifications and bandwidths. The impact is amplified in municipalities ideologically aligned with state and federal governments. We provide suggestive evidence that reduced ties to agribusiness and voter preferences may explain these results. Our findings contribute to the literature on political determinants of environmental policy and underscore the importance of local governments in advancing environmental protection in decentralized governance contexts.


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
