
---
title: "Assignments"
permalink: /assignments/
layout: archive
author_profile: true
---

{% assign posts = site.categories.Assignments %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}