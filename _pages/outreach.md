---
layout: archive
title: "Outreach"
description: "Speaking engagements, media appearances, and outreach activities"
permalink: /outreach/
author_profile: true
---

{% include base_path %}

## Outreach & Speaking

I'm passionate about sharing my research and engaging with the community. You can find an updated list of my outreach activities on my [CV](/files/CV_JTorres.pdf).

{% for post in site.misc reversed %}
  {% include archive-single.html %}
{% endfor %}
