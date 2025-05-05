---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

An up to date list can be found on <a href="https://scholar.google.com/citations?user=EwvaTJQAAAAJ&hl=en">Google Scholar</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
