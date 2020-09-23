---
layout: archive
title: "misc"
permalink: /misc/
author_profile: true
---

{% include base_path %}

{% for post in site.misc reversed %}
  {% include archive-single.html %}
{% endfor %}
