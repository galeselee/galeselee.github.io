---
layout: archive
#title: "blog"
permalink: /Blog/
author_profile: true
---

{% include base_path %}

{% for post in site.blog reversed %}
  {% include archive-single.html %}
{% endfor %}