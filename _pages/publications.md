---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Most of these publications may also be found on my <u><a href="https://scholar.google.com/citations?authuser=1&user=RNE48wsAAAAJ">google scholar profile</a>.</u>
This repository contains my learning notes.
---
{% include base_path %}

{% for post in site.notes reversed %}
  {% include archive-single.html %}
{% endfor %}

