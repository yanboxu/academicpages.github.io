---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

  You can find a full list of my publications on <u><a href="https://scholar.google.com/citations?user=x1QnFEcAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
