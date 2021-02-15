---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on my [(Google Scholar Profile)](https://scholar.google.de/citations?user=OcVBk1MAAAAJ&hl=en)
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
