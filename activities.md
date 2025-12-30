---
layout: archive
title: "Activities"
permalink: /activities/
author_profile: true
---

{% include base_path %}

{% for post in site.activity reversed %}
  {% include archive-single-activity.html %}
{% endfor %}

