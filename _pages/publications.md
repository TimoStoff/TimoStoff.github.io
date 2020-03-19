---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  My work can also be viewed on <u><a href="{{site.author.googlescholar}}" target="_blank"> Google Scholar</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-custom.html %}
{% endfor %}
