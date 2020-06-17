---
layout: archive
title: "Works"
permalink: /work/
author_profile: true
---
Past works will be added in this page recently

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
