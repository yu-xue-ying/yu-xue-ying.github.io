---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find our articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

You can also find our articles on [my Google Scholar profile](https://scholar.google.com/citations?user=xjZnukgAAAAJ&hl=en&oi=ao).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
