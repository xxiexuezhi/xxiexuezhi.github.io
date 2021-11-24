---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---
This repository contains my learning notes.
---
---
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

