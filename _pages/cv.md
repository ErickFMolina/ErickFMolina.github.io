---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
paperurl: 'http://ErickFMolina.github.io/files/CV_ErickFMolina_Dec23.pdf'
---

{% include base_path %}

You can find my CV here

{% for post in site.publications reversed %}
  {% include CV_ErickFMolina_Dec23.pdf %}
{% endfor %}
  
