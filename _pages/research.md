---
layout: archive
title: "Research and presentations"
permalink: /research/
author_profile: true
---

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
