---
layout: archive
title: "Reseach"
permalink: /publications/
author_profile: true
---

[De Olho Nas Urnas: Observatory of the Presence of Women in Politics in the Municipal Elections of 2024 ](https://deolhonasurnas.ufg.br/)

The project's objective is to monitor the candidacies of women councilors, compliance with gender quotas, and the promotion of female participation in political parties. We also monitor the main types of violence (physical, psychological and economic) that affect women in politics.


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
