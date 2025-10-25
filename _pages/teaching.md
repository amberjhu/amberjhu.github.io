---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<h1><a href="/files/Hu_Teaching_Statement.pdf">Teaching Statement</a></h1>
<p>Last updated October 2025</p>

{% for post in site.teaching reversed %}
  {% if post.academic_term %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
