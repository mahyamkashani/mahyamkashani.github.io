---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my all presentation on <a href="{{https://www.slideshare.net/mahyamk}}">my slides in SlideShare</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
