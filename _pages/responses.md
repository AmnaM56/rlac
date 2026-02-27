---
title: "Responses"
permalink: /responses/
layout: archive
author_profile: true
---

Here are all my responses for the course.

{% assign posts = site.categories.responses %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}