---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: false
redirect_from: 
#   - /experience/
  - /experience.html
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.experience reversed %}
  {% include archive-single.html %}
{% endfor %}