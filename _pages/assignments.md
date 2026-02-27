
---
title: "Assignments"
permalink: /_posts/
layout: archive
author_profile: true
---


{% assign posts = site.categories.assignments %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}