---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find my articles on <u><a href="{{ site.author.googlescholar }}" target="_blank">my Google Scholar profile</a></u> and <u><a href="{{ site.author.researchgate }}" target="_blank">my ResearchGate profile</a></u>.

{% comment %}
You can also find my articles on <u><a href="{{ site.author.googlescholar }}" target="_blank">my Google Scholar profile</a>.</u>
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
