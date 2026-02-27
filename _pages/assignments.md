---
title: "Assignments"
permalink: /assignments/
layout: archive
author_profile: true
---

Here are all my assignments for the course.

{% assign assign_posts = site.posts | where_exp: "item", "item.categories contains 'assignments'" | sort: 'date' | reverse %}

{% for post in assign_posts %}
  {% include archive-single.html %}
{% endfor %}